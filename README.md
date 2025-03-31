# The-Answer-to-Everything-
import random

def generate_question(): operations = ['+', '-', '*', '//']  # Integer division to keep it simple while True: num1 = random.randint(1, 200) num2 = random.randint(1, 200) op = random.choice(operations)

if op == '+':
        if num1 + num2 == 143:
            return f"{num1} + {num2} = ?"
    elif op == '-':
        if num1 - num2 == 143:
            return f"{num1} - {num2} = ?"
    elif op == '*':
        if num1 * num2 == 143:
            return f"{num1} * {num2} = ?"
    elif op == '//' and num2 != 0:
        if num1 // num2 == 143:
            return f"{num1} // {num2} = ?"

Generate and print a question

print(generate_question())

