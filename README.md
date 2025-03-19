def add(x, y):
    return x + y

def subtract(x, y):
    return x - y

def multiply(x, y):
    return x * y

def divide(x, y):
    return x / y

print("Select which operation you would like to use.")
print("Would you like to add?")
print("Would you like to sub?")
print("Would you like to multiply?")
print("Would you like to divide?")

pick = input("Enter an operation: ")

x= int(input("Enter first number: "))
y = int(input("Enter second number: "))

if pick == 'add':
    print(x, "+", y, "=", add(x, y))
elif pick == 'subtract':
    print(x, "-", y, "=", subtract(x, y))
elif pick == 'multiply':
    print(x, "*", y, "=", multiply(x, y))
elif pick == 'divide':
    print(x, "/", y, "=", divide(X, y))
else:
    print("Inputted wrong")
