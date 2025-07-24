#sumhead recursion
def sumhead(n):
    if n==0:
        return 0
    return n+sumhead(n-1)    
num=int(input("enter a number:"))
print("sum:",sumhead(num))
''''''''output''''''''''
enter a number: 4                                          sumhead(<h>====4+3+2+1=10)
sum: 10



#sumtail recursion
def sumtail(n,temp=0):
    if n==0:
        return temp
    return sumtail(n-1,temp+n)    
num=int(input("enter a number:"))
print("sum:",sumtail(num))
''''''''output''''''''''                                   sumtail)<t>========1+2+3+4+5+6+=21)
enter a number: 6
sum: 21


#calculating the both sumhead and sumtail
#sumhead recursion
def sumhead(n):
    if n==0:
        return 0
    return n+sumhead(n-1)    
num=int(input("enter a number:"))
print("sum:",sumhead(num))
#sumtail recursion
def sumtail(n,temp=0):
    if n==0:
        return temp
    return sumtail(n-1,temp+n)    
num=int(input("enter a number:"))
print("sum:",sumtail(num))
''''''''output'''''''''' 
enter a number: 5         (<h>==5+4+3+2+1=15)                          
sum: 15
enter a number: 10        (<t>==1+2+3+4+5+6+7+8+9+10=55)
sum: 55
