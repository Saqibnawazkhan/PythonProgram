
print("\t\t *** Calculator ***")

while True:
    

    op = int(input("Press 1 for addition\nPress 2 for Subtraction\nPress 3 for Multiplitcation\nPress 4 for Division\nPress 5 to exit\n----> \n\n"))
    num1 = int(input("Enter 1st Number: "))
    num2 = int(input("Enter 2nd Number: "))

    if op == 1:
        sum = num1 + num2
        print("Sum is: ", sum)
    
    elif op == 2:
        sub = num1 - num2
        print("Sub is: ", sub)
    
    elif op == 3:
        mul = num1 * num2
        print("Multiple is: ", mul)
    
    elif op == 4:
        div = num1 / num2
        print("division is: ", div)
        
    elif op == 5:
        break

   

