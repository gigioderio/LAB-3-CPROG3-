# Part 1: Simple Function (No parameter)
def personal_details():
    print("Name: Gigi Oderio")
    print("Age: 20")
    print("Grade: BSCS 2-A")
    print("School: UA-TLMC")
    print("Address: Bitadton Sur, Culasi, Antique")


# Part 2: Function with Parameters
def show_details(name, age, grade, school, address):
    print("\nPersonal Details:")
    print("Name:", name)
    print("Age:", age)
    print("Grade:", grade)
    print("School:", school)
    print("Address:", address)


# Part 3: Function with Return Value
def add(a, b):
    return a + b


# Part 4: Function with User Input (Average of 3 numbers)
def compute_average():
    num1 = float(input("\nEnter first number: "))
    num2 = float(input("Enter second number: "))
    num3 = float(input("Enter third number: "))
    return (num1 + num2 + num3) / 3


# Part 5: Mini Calculator Functions
def subtract(a, b):
    return a - b

def multiply(a, b):
    return a * b

def divide(a, b):
    if b == 0:
        return "Cannot divide by zero"
    return a / b


# Main Program
personal_details()

show_details("Gigi Oderio", 20, "BSCS 2-A", "UA-TLMC", 
             "Bitadton Sur, Culasi, Antique")

result = add(5, 3)
print("\nAddition Result:", result)

avg = compute_average()
print("Average:", avg)

print("\nMini Calculator")
x = float(input("Enter first number: "))
y = float(input("Enter second number: "))

print("Add:", add(x, y))
print("Subtract:", subtract(x, y))
print("Multiply:", multiply(x, y))
print("Divide:", divide(x, y))
