'''char=(input('enter the CHARECTER :'))
print("the ASCII value of:",ord(char))

n=int(input('enter the value:'))
for i in range(65,n+1,1):
 print(chr(i))'''


#python program for sum of square of first n nutural numbers
'''n=int(input('enter the number:'))
sum=0
for i in range(1,n+1):
    sum+=(i)**2
    print(sum)'''


#write a python program to swap two number using bitwise operter
'''n=int(input('enter the number:'))
count=0
rev=0
while(n!=0):
 count=n%10
 rev=rev*10+count
 n//=10
 print(rev)'''


# write a program to check the number is alphabet or not
'''s1=input('enter the value:')
x=s1.isalpha()
print(x)'''


#write a program to input any alphabet char. and to check weather it is vowel or consonent
'''s1=input("enter the alphabet :")
vowel='aeiouAEIOU'
vc=0
cc=0
for i in s1:
 if(i in s1):
    vc+=1
else:
 cc+=1
print("vowel",vc)
print("onsonent",cc)'''


#dicosnery
'''s={'ram':{'class':12,'roll no':4568,'mob.':8958944091}}
print(s)
print(type(s))
s1={'name=':'tanak','class=':'45','mob=':154652546}
for i in s1.values():
 print(i)
for a,b in s1.items():
    print(a,b)
print(len(s1))
print(max(s1))
print(min(s1))
print(sorted(s1))
c=s.update({'name':'ram'})
print(c)
s1[12]='mnj'
print(s1)
s1.update({'name=':'ram'})
print(s1)
s1.pop('name=')
print(s1)
s2={'a':1,'b':2,'c':3,'d':4}
for h,f in s2.items():
 s2.pop(h)
 print(s2)
count=0
for i in range(1,6):
 s1=('math','science','english','sst','hindi')
 n=int(input('enter the marks=='))
 count+=n
if(n>=90):
 print(n,'grade A')
elif(n >= 80):
 print(n,'grade B')
elif(n >= 70):
 print(n,'grade c')
elif(n >= 60):
 print(n,'grade d')
if (n >= 50):
 print(n,'grade E')
elif(n<40):
 print(n,'grade F')
 per=((count/500)*100)
 print('percentage=',per)'''


#ASCII=============
'''f=int(input('enter the first value:'))
s=int(input('enter the value:'))
for i in range(f,s+1,1):
 print(chr(i))'''

#write a python program to find first and last digits of number
'''print("enter the number:")
num=int(input())
count=0
while num!=0:
     if count==0:
         last=num%10
         count+=1
     rem=num%10
     num=int(num/10)
     print(rem,last)'''

'''import math
num=int(input('enter the number:'))
first=num%10
last=num//(10**math.floor(math.log10(num)))
print("first=", first,",","last=",last)'''


#15
'''x=int(input('enter the value:'))
y=int(input('enter the value:'))
sum=x+y
print("sum of number=",sum)'''


#16
'''x=int(input('enter the value:'))
y=int(input('enter the value:'))
product=x*y
print("sum of number=",product)'''

#17
'''n=int(input("enter the number:"))
count=0
while n!=0:
    rev=n%10
    n//=10
    print(rev,end="")'''

#18
'''n=int(input("enter the number:"))
mat=n
rev=0
while n!=0:
 digit= n % 10
 rev=rev*10+digit
 n //= 10
if(mat==rev):
     print("palendrome number")
else:
    print("not palendrone number")'''

#19
#write a python programing to find factors of the number
'''n=int(input("enter the number:"))
factor=0
for i in range(1,n):
 if(n%i==0):
       print(i,end=" ")'''

#20
#write a python proggaming to find factorial of the number
'''n=int(input("enter the number:"))
fact=1
for i in range(1,n+1,):
     fact*=i
     print(fact)'''

#21,23
#write the LCM and HCF in python programing
'''n=int(input('enter the number:'))
x=int(input('enter the number:'))
y=int(input('enter the number:'))
lcm=1
for i in range(1,n+1):
    if(x%i==0 and y%i==0):
        lcm=i
        break
print(lcm,end=",")
     #hcf= (x*y)/lcm
   # print(hcf)'''

#23
#A number is prime or not prime number
'''n=int(input('enter the number:'))
count=1
for i in range(1,n+1):
    if n%i==0:
     count+=1
    elif count==2:
          print("***prime number***")
    else:
          print("*** is not prime number*** ")'''

#24

n=int(input('enter the number:'))
count=1
if n==1:
    print("prime number")
else:
 for i in range(1,n+1):
    if n%i==0:
     count+=1
    elif count==2:
          print()










