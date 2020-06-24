# AI
# Fibonacci series-python
n=int(input())
a=-1
b=1
c=a+b
while (c<=n):
    n=n+1
    print(c, end=',')
    a=b
    b=c
    c=a+b
    
