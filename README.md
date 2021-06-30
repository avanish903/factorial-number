# factorial-number
#find factorial br itarative and recursive method
v=int(input("enter a number:\n"))
def factorial1(n):
    fact=1
    for i in range(n):
        fact=fact*(i+1)
    return fact
    # print(fact)
print("factorial by itarative method", factorial1(v))    


def factorial2(n):
    if n==1:
        return 1
    else:
        return n*factorial2(n-1)

print("factorial by recursive method",factorial2(v))        
