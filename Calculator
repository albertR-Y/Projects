# Program make a simple calculator

#All inputs & calculations are stored within this function
def Calculate():
    # Getting the first integer
    Number_1 = int(input("Please Input Your First Number: "))

    # Showcasing the type of operators we can use and store it into a variable
    Operators = input("""
    +, plus (addition)
    −, minus (subtraction)
    /, obelus (division)
    *, times (multiplication)
    """)

    # If the input does not contain any of the Operators, it will loop again until users inputs the correct character
    while Operators not in ("+", "-", "/", "*"):
        Operators = input("Please Select One Of The Following: ")
        if Operators in ("+", "-", "/", "*"):
            continue
        else:
            break

    # Getting the second integer
    Number_2 = int(input("Please Input Your Second Number: "))

#This adds two numbers
    if Operators == "+":
        print(f"{Number_1} {Operators} {Number_2}")
        print(round(Number_1 + Number_2))

#This subtracts two numbers
    elif Operators == "-":
        print(f"{Number_1} {Operators} {Number_2}")
        print(round(Number_1 - Number_2))

#This multiplies two numbers
    elif Operators == "*":
        print(f"{Number_1} {Operators} {Number_2}")
        print(round(Number_1 * Number_2))

#This divides two numbers
    else:
        print(f"{Number_1} {Operators} {Number_2}")
        print(round(Number_1 / Number_2))
#Runs the Use again funcion
    try_again()


def try_again():
    again = input("Do You Want To Use This Again? (Y/N) ")
    while again.lower() not in ("y", "yes", "n", "no"):
        again = input("Do You Want To Use This Again? (Y/N) ")
    if again.lower() in ("yes", "y"):
        return Calculate()
    else:
        print("Good Bye")


Calculate()
