# First-simple-python-calculator
"""
simple calculator using python
"""

print("____________Calcualator_______________")
print("\n")
a= int(input("ENter a number"))
b=int(input("ENter another number"))
c=input("What will you do(+,-,/,*,%,//) ")

if(c=="+"):
  sum=a+b
  print("The sum is", sum)

elif(c=="-"):
  diff=a-b
  print("The difference is", diff)

elif(c=="*"):
  mul=a*b
  print("The multiplication is", mul)

elif(c=="/"):
  div=a/b
  print("The division is", div)

elif(c=="%"):
  rem=a%b
  print("The remainder is", rem)

else:
   int_quotient=a//b
   print("The integer is", int_quotient) 
# quotient without decimal
