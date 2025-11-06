name=(input("Please enter your name: "))
print("Welcome" , name)
choice=(input("What do you want to do ? (Addition , Subtraction , Multiplication , Division )"))

x=int(input("Please enter the first digit: "))
y=int(input("Please enter the second digit: "))

if choice == "Addition":
    print(x+y)     

elif choice.lower() == "addition":   
    print(x+y)      

if choice == "Subtraction":
    print(x-y)             

elif choice.lower() == "subtraction":
    print(x-y)

if choice =="Multiplication":
    print(x*y)     

elif choice.lower() == "multiplication":
    print(x*y)            

if choice =="Division":
   print(x/y)

elif choice.lower() == "division":
    print(x/y)

print("Thanks for using this calculator")
