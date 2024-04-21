# Internship-projects
#Task1 
#Fibonacci Series Generator
def fibonacci_generator(n):
    fib_sequence = [0, 1]
    while len(fib_sequence) < n:
        fib_sequence.append(fib_sequence[-1] + fib_sequence[-2])
    return fib_sequence[:n]

# Take input from the user
n = int(input("Enter the number of Fibonacci numbers to generate: "))
fib_numbers = fibonacci_generator(n)
print("Fibonacci sequence:", fib_numbers)
