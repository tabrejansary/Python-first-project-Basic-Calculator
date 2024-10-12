print("Select an operation to perform:")
print("1.ADDITION")
print("2.SUBTRACTION")
print("3.MULTIPLICATION")
print("4.DIVISION")
print("5.MODULUS or REMAINDER")
print("6.FLOOR DIVISION")
print("7.EXPONENTIAL")

operation = int(input())
#addition
if operation == 1:
  num1=int(input("Enter the first number"))
  num2=int(input("Enter the second number"))
  addition=num1+num2
  print("addition of",num1,"and",num2,"is:",addition)

#subtraction
elif operation == 2:
  num1=int(input("Enter the first number"))
  num2=int(input("Enter the second number"))
  subtraction=num1-num2
  print("subtraction of",num1,"and",num2,"is:",subtraction)

#multiplication
elif operation == 3:
  num1=int(input("Enter the first number"))
  num2=int(input("Enter the second number"))
  multiplication=num1*num2
  print("subtraction of",num1,"and",num2,"is:",multiplication)

#division
elif operation == 4:
  num1=int(input("Enter the first number"))
  num2=int(input("Enter the second number"))
  if num2!=0:
    division=num1/num2
    print("division of",num1,"by",num2,"is:",division)
  else:
    print("division by zero is not possible")

#Modulus
elif operation == 5:
  num1=int(input("Enter the first number"))
  num2=int(input("Enter the second number"))
  modulus=num1%num2
  print("Remainder of",num1,"and",num2,"is:",modulus)

#Floor division
elif operation == 6:
  num1=int(input("Enter the first number"))
  num2=int(input("Enter the second number"))
  flrdiv=num1//num2
  print("The division of", num1, "and",num1,"without any remainder is:",flrdiv)

#Exponential for cube 
elif operation == 7:
  num1=int(input("Enter the number"))
  n=int(input("Enter the exponential power"))
  exp1=num1**n
  print("The exponent result of ",num1,"is:",exp1)

else:
  print("Invalid Entry")

print("Thanks for using my calculator! message:@Tbrz")
