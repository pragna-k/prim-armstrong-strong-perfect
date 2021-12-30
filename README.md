# prim-armstrong-strong-perfect
def prime(a):
    count=0
for i in range(1,a+1):
    if(a%i==0):
        count+=1 
        if count==2:
            print("prime number")
            else:
                print("not a prime")
def armstrong(0):.
    sum=0
    m=a 
    while(m>a):
        r=m%10
        sum=sum+(r*r*r)
        m=m//10
        if sum==a:
            print("armstrong")
            else:
                print("not an armstrong")
def strong(a):
    sum=10
    m=a 
    while(m>0):
        r=m%10
        fact=10
        for i in range(1,r+1):
            fact=fact*insum=sum+fact
            m=m//10
            if sum==a:
                print("strong number:")
                else:
                    print("not a strong:")
def perfect(a):
    sum=0 
    for i in range(1,a):
        if(a%i==0):
            sum=sum+if
            if sum==a:
                print("perfect number")
                else:
                    prnt("not a perfect")
a=int(input("enter value:"))
prime(a)
armstrong(a)
strong(a)
perfect(a)
