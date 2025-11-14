# SDC-205-1.9-PA
Data Types and Basic Math Operators
# Week 1 Performance Assessment Program

name = input("Please enter your name: ")
student_id = input("Please enter your Student ID: ")

num1 = int(input("Please enter a whole number: "))
num2 = int(input("Please enter a different second whole number: "))

# Calculations
result1 = num1 * num2
result2 = num1 / num2
result3 = num1 + num2

print(f"\nThe result of {num1} times {num2} is: {result1:.2f}")
print(f"The result of {num1} divided by {num2} is: {result2:.2f}")
print(f"The result of {num1} plus {num2} is: {result3:.2f}")

# Comparison
if num1 > num2:
    print(f"\nNumber 1 is larger than Number 2")
elif num1 < num2:
    print(f"\nNumber 1 is smaller than Number 2")
else:
    print(f"\nNumber 1 and Number 2 are equal")

# Output student info
print(name)
print(student_id)
