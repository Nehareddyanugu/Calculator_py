# Calculator_py
Day 01:simple python calculator program!!
num1=int(input("enter number 1: "))
num2=int(input("enter number 2: "))
print("enter num according to the req operation:\n1.Addition\n2.Subtraction\n3.Multiplication\n4.Division\n5.Power of num")
num=int(input("enter your choice:"))
match num:
    case 1:print(f"addition of {num1} and {num2} is {num1 + num2}")
    case 2:print(f"subtraction of {num1} and {num2} is {num1-num2}")
    case 3:print(f"multiplication of {num1} and {num2} is                {num1*num2}") 
    case 4:print(f"division of {num1} and {num2} is {num1/num2}")
    case 5:
             if num1>num2:
                print(f"{num1} power {num2} is {num1**num2}")
             else:
                print(f"{num2} power {num1} is {num2**num1}")
    case _:print(f"invalid choice")  
    
    
