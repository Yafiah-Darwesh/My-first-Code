# My-first-Code
First code which is a calculator
num1 = int(input("Enter your first number: "))
num2 = int(input("Enter your second number: "))
num_operator = (input("choose + , - , / , *: "))

if num_operator == "+":
    print("Addition is:", num1+num2)
    
if num_operator == "/" and num2 == 0:
    print("revise your number")

elif num_operator == "/":
    print("Division is:", num1/num2)
    
elif num_operator == "*":
    print("Multiplication is:", num1*num2)

elif num_operator == "-":
    print("Subtraction is:", num1 - num2)
