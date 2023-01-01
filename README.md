# python_calculator
def calculator():
    number1 = float(input("give me first number: "))
    number2 = float(input("give me second number: "))
    operator = input("provide any of them +-/*: ")

    if operator == '+':
        result = number1 + number2
    elif operator == '-':
        result = number1 - number2
    elif operator == '*':
        result = number1 * number2
    elif operator == '/':
        result = number1 / number2
    else:
        print("invalid operator: ")
        return

    print(number1,operator,number2, "=", result)

calculator()
