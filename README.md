# Calculator
a basic calculator using python
a = int(input("Enter First number here : "))
if(a%2 == 0):
  print("The first number", a, "is even")
else:
    print("The first number", a, "is odd")
b = int(input("Enter Second number here : "))
if(b%2 == 0):
    print("The second number", b, "is even")
else:
    print("The second number", b, "is odd")
print("the sum of the two given numbers is", float(a) + float(b))
print("the difference between the two given numbers is", float(a) - float(b))
print("the product of the two given numbers is", float(a)*float(b))
print("the quotient when the first number is divided by the second number is", float(a)/float(b))
print("the remainder when the first number is divided by the second number is", float(a)%float(b))
print("the floor division quotient when the first number is divided by the second number is", float(a)//float(b))
print("the first number to the power of the second number is", float(a)**float(b))
