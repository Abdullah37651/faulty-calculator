# faulty-calculator
print("enter first number")
num1=int(input())
print("enter operation'+,-,*,/'")
operator=input()
print("enter second number")
num2=int(input())

if num1==45 and num2==3 and operator=='*':
    print("555")
elif num1==56 and num2==9 and operator=='+':
    print("77")
elif num1==56 and num2==6 and operator=='/':
    print("4")
elif operator=='+':
    sum=num1 + num2
    print(sum)
elif operator=='-':
    sub=num1-num2
    print(sub)
elif operator=='*':
    mul=num1*num2
    print(mul)
elif operator=='/':
    div=num1/num2
    print(div)
else:
    print("error,check your input")
