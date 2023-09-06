# Create Add function
def add_numbers(num1, num2):
    return num1 + num2
#Create Subtract Function
def subtract_numbers(num1, num2):
    return num1 - num2
#Create Multiply Function
def multiply_numbers(num1, num2):
    return num1 * num2
#Create Divide Function
def divide_numbers(num1, num2):
    return num1 / num2
#Create Exponent Function
def exponent_numbers(num1,num2):
    return num1 ** num2
#Create Root Function # x ** (1/n) is how to find roots
def root_numbers(num1,num2):
    return num1 ** (1/num2)

def main():
    print("CALCULATOR SIMULATION")
    print("Select operation.\n 1.Add\n 2.Subtract \n 3.Multiply \n 4.Divide \n 5.Exponential num1 ^ num2\n 6.Root num2 of num1")

    user_response = 'y'
    while user_response.lower() == 'y' or user_response.lower() == 'yes':

        user_input = float(input("Enter choice(1/2/3/4/5/6):")) #Get operation selection from user
        num1 = float(input("Enter first number:")) #User inputs first number
        num2 = float(input("Enter second number:")) #User inputs second number



        if user_input == 1:
            total = add_numbers(num1,num2)
            print(num1, "+" ,num2 ,"=", total)
        elif user_input == 2:
            subtract_numbers(num1,num2)
            print(num1, "-", num2, "=", subtract_numbers(num1,num2))
        elif user_input == 3:
            multiply_numbers(num1,num2)
            print(num1, "*", num2, "=", multiply_numbers(num1,num2))
        elif user_input == 4:
            divide_numbers(num1,num2)
            print(num1, "/", num2, "=", divide_numbers(num1, num2))
        elif user_input == 5:
            exponent_numbers(num1,num2)
            print(num1, "^", num2, "=", exponent_numbers(num1, num2))
        elif user_input == 6:
            root_numbers(num1,num2)
            print(num2, "root of", num1, "=", root_numbers(num1, num2))
        else:
            print("Invalid Input")

        play_again =input("Would you like another calculation? (y/n):")
        user_response = play_again

    print("Thanks for using this calculator simulation")






main()



