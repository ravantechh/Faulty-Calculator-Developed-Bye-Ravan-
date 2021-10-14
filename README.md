# Faulty-Calculator-Developed-Bye-Ravan-
def calculetor():
    print("\nWellcome to Calc: This Developed By Ravan")
    operation = input('''
    Hane Apke Liye Ek Special Calculator Banaya hai Aap Iasme Kuchh Multipal Operation Kiya ja sakata Hai:
    + for addition
    - for subtraction
    * for multiplication
    / for division
    ** for power
    % for modulo
    Apna Vikalp Chune:
    ''')

    number1 = int(input("Enter first Number: "))
    number2 = int(input("Enter second Number: "))

    if operation == '+':
        if number1 == 56:
            print("56 + 9 = 77")
        else:
            print(f"{number1} + {number2} = {number1 + number2}")
    elif operation == '-':
        print(f"{number1} - {number2} = {number1 - number2}")
    elif operation == '*':
        if number1 == 45:
            print("45 * 3 = 555")
        else:
            print(f"{number1} * {number2} = {number1 * number2}")
    elif operation == '/':
        if number1 == 56:
            print("56/6 = 4")
        else:
            print(f"{number1} / {number2} = {number1 / number2}")
    elif operation == '**':
        print(f"{number1} ** {number2} = {number1 ** number2}")
    elif operation == '%':
        print(f"{number1} % {number2} = {number1 % number2}")
    else:
        print("OH! Apne Galat Key ko Dabaya Hai")
    again()


def again():
    cal_again = input('''
    Agar aap fir se koi bhi Calculation karana Chahte hai to?
    Kripaya Y likhe  Ha ke liye our nahi ke liye N .
    ''')

    if cal_again == 'Y':
        calculetor()
    elif cal_again == 'N':
        print("Chal Bete Bad Mei Milate Hain:\n")
    else:
        again()


calculetor()
#Tahnk You Harry Sir 
