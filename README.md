print("Simple Calculator")

while True:
    print("\n1.Add")
    print("2.Subtract")
    print("3.Multiply")
    print("4.Divide")
    print("5.Exit")

    choice = int(input("Enter your choice: "))

    if choice == 5:
        print("Program Ended")
        break

    a = float(input("Enter first number: "))
    b = float(input("Enter second number: "))

    if choice == 1:
        print("Addition =", a + b)

    elif choice == 2:
        print("Subtraction =", a - b)

    elif choice == 3:
        print("Multiplication =", a * b)

    elif choice == 4:
        if b == 0:
            print("Cannot divide by zero")
        else:
            print("Division =", a / b)

    else:
        print("Invalid Choice")





challenge 2
print("Simple Calculator")

while True:
    print("\n1.Add")
    print("2.Subtract")
    print("3.Multiply")
    print("4.Divide")
    print("5.Exit")

    choice = int(input("Enter your choice: "))

    if choice == 5:
        print("Program Ended")
        break

    a = float(input("Enter first number: "))
    b = float(input("Enter second number: "))

    if choice == 1:
        print("Addition =", a + b)

    elif choice == 2:
        print("Subtraction =", a - b)

    elif choice == 3:
        print("Multiplication =", a * b)

    elif choice == 4:
        if b == 0:
            print("Cannot divide by zero")
        else:
            print("Division =", a / b)

    else:
        print("Invalid Choice")