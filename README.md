#program 1(with pre defined variables)

#num1=30
#num2=40
#sum=num1+num2
#print("thesum of given two number is  ", sum)


#program2(with user input)

#num1=float(input("enter a number here: "))
#num2=float(input("enter another number here: "))
#sum=num1+num2
#print("the sum of the provided two numbers is", sum)

#3 program to print hello world

#print("hello world")

#solution1(using exponentiation)

#um=64
#num1=int(input("enter a number here:"))
#sr=num**0.5
#print("the square root of the given number is",sr)

#solution2(use math module )

#import math
#num=int(input("enter a number here: "))
#sr=math.sqrt(num)
#print("the sqrt of a given number is",sr)

#calculate the area of triangle

#hight=float(input( "enter the height of the triangle:"))
#base=float(input("enter the base of the triangle: "))

#area=(0.5)*base*hight
#print('the area of triangle is',area)

#quadratic equation ax**2 + bx + c=0 
#a, b and c are real numbers
#a!=0

#import cmath

#a=int(input("enter a number (a!=0): "))
#b=int(input("enter number: "))
#c=int(input("enter the number: "))

#formula for discriminant
#d=(b**2)-(4*a*c)
#root1=(-b-cmath.sqrt(d))/(2*a)
#root2=(-b+cmath.sqrt(d))/(2*a)

#print("the roots are", root1 , root2)


#python program to swap 2 variables

#x=int(input("enter the input x:",))
#y=int(input("enter the input y:",))
 
#temp=x
#x=y
#y=temp

#print("the value ofx is", x)
#print("the value of y is", y)

#solution2(with out using third variable  ex temp)
#x=1
#y=2

#x,y = y,x

#print(x)
#print(y)


#python program to generate random numbers
#(using random module)

#import random
#num = random.randint(0,10)
#print(num)

#python progrm to convrt kilometer to miles
#(1km=0.621371 miles)

#km=float(input("enter in km"))
#miles=(0.621371)*km
#print(km, "kms in miles will be", miles,"miles")

#python program to convert celsius to fahrenhit
#(0celsius = 32farhanite)
#cell=int(input("enter the value in fahrenhit", ))
#farr=(cell*(9/5))+32
#print(cell, "in farhanite is", farr,"farahanite")


#program to check number is positive negative or 0
#(using onditional statement)

#num=int(input("enter the number", ))
#if  num>0:
#    print("positive") 
#elif num<0:
#    print("negative")
#else:
#    print("zero")                           #if  condition:
                                          #body


#check if a number is odd or even
#(num%2=0 even)

#num=int(input("enter the number",))
#if(num%2 == 0):
#    print("even number")
#else :
#    print("odd number")


#program to check leap year
#(leap year 366 once in 4 year num%400==0 & num%100==0)

#year=int(input("enter the year", ))
#if  (year%400==0) and (year%100==0):
#    print("leap year")
#elif (year%400==0) and (year%100 !=0 ):
#    print("leap year")
#else:
#    print("not a leap year")



#conditional statements 1hour
#num2=int(input("Enter the second value", ))
#num3=int(input("enter the 3rdvalue", ))

#if num1>num2 and num1>num3 :
#   print("num 1 is gratest")
#elif num2>num1 and num2>num3:
#    print("num2 is grater")
#else:
#    print("num3 is grater")


#check prime number
#number divide by any other numer not zero(3,5,7,11,13,17 etc)
# num%1,3,4,..............!=0 is prime

#num=int(input("enter the number:", ))
#if num==1:
#     print("it is not a prime")
#if num>1:
#    for i in range(2,num):
#        if num%i==0:
#            print("not prime")
#            break
#    else:
#        print("prime")

#program to print all prime numbers in a interval
#range(lower,higer+1)

#lower=int(input("enter the lower number", ))
#higer=int(input("enter the higher number", ))

#for num in range(lower,higer+1):
#    if num>1:
#        for i in range(2,num):
#            if num%i==0:
#                break
#        else:
#            print(num)


#program to find factorial of a number 1:22
#(5!= 5*4*3*2*1)
#num<0,num==0is1


#using for loop
#num=int(input("enter the input", ))
#fact=1
#if num<0:
#    print("invalid number")
#if  num==0:
#    print("1")
#if num>0:
#    for i in range(1,num+1):
#        fact=fact*i
#print("the factorial of a number is:", fact)

#using recursion..................................................................................................................................................

#def fact(a):
#    if a==0:
#        return 1
#    else:
#        return ((a)*fact(a-1))
#    
#num = int(input("enter a number heree ",))   
#result=fact(num)
#print("factorial is: ", result)
   


#program to display the multiplication table
#for loop(7*1=1,7*2=14)

#num=int(input("enter the input:",))
#for i in range(1,11):
#    print(num,"*",i,"=",num*i)
 
#using while loop
#while i<=10
#condition

#num=int(input("enter the value", ))
#i=1
#while i<=10:
#    print(num,"*",i,"=",num*i)
#    i=i+1    

#program for fibonaki series
#(0,1,1,2,3,5,8)

#num=int(input("enter the range", ))
#a=0
#b=1

#if num==1:
#    print(a)
#else:
#    print(a)
#    print(b)
#    for i in range(1,num+1):
#        c=a+b
#        a=b
#        b=c
#        print(c)

#program to check amstrong number
#(amstrong number:ex:153=(1*1*1)+(5*5*5)+(3*3*3))ex:52=5*5+2*2
#if 

#num=int(input("enter the input", ))
#ord=len(str(num))##convert number  to string
#sum=0
#temp=num

#while temp>0:
#    digit = temp%10
#    cube=digit**ord
#    sum=sum+cube
#    temp//=10

#if sum == num:
#    print("amstrng number")
#else:
#    print("not amstrong number")


#amstrong number in a interval
#logic num=407,order=len(str(num)sum=0,temp=num,digit=temp%10,cube=digit**order,sum+=cube,temp//=10

'''lower=int(input("enter the lower limit here: "))
upper=int(input("enter the upper limit: "))


for num in range(lower,upper+1):
    ord=len(str(num))
    sum=0
    temp=num
    while temp>0:
        digit=temp%10
        cube=digit**ord
        sum=sum+cube
        temp//=10
    if num==sum:
        print(num)
'''


#sum of natural numbers
#natural number is positive intiger

'''num=int(input("enter the number: "))
if num<0:
    print("not natural")
else:
    sum=0
    while num>0:
        sum+=num
        num-=1
    print(sum)'''


#program to dispay powers of 2 using Anonymous function
#lamda function is anonymous function

'''nterms=int(input("enter the number of terms: "))

result=list(map(lambda x : 2**x, range(nterms+1)))
print(result)

for i in range(nterms+1):
    print("the value of 2 raised to power",i,"is",result[i])
'''


#find the number divsable by anothr number


'''for i in range(1,100):
    if i%13==0:
        print(i)'''

#by using lamda function and filter

'''l=[39,48,26,98,33,67,87]
result=list(filter(lambda x:x%13==0,l))
print(result)'''

#program to convert decimal to binary,octal and hexadecimal
'''decimal=int(input('enter a number: '))
print("the conersation of decimal number",decimal,"is: ")
print(bin(decimal),"in binary")
print(oct(decimal),"in octal")
print(hex(decimal),"in hexadecimal")
'''

#program to find ASCII value of character
#using ord function(ord is used)
'''
char=str(input("enter the string: "))
print("the ASCII value of",char, "is", ord(char))
'''

#program to find HCF / GCD
#(ex 12 highest common factor) use def ex 12,30  6 is hcf

'''def findhcf(x,y):
    if x>y:
        smaller=y
    else:
        smaller=x
    for i in range(1,smaller+1):
        if((x%i==0) and (y%i==0)):
            hcf=i
    return hcf

x=12
y=30

print("the hcf of given two number is",findhcf(12,13))
   '''

#factor of a number

'''num =int(input("enter the number: "))

for i in range(1,num+1):
    if num%i==0:
        print("the output is",i)'''

#program to make simple calculator

'''print("minimal calculator")

num1=int(input("enter first number: "))
num2=int(input("enter the second number: "))
print("press 1 for addition \npress 2 for subtraction \npress 3 for multiplication \n press 4 for division")

choice=int(input("enter your choice 1-4: "))
if choice==1:
    print(num1+num2)
elif choice==2:
    print(num1-num2)
elif choice==3:
    print(num1*num2)
else:
    print(num1/num2)
'''

#program to shuffle deck of cards
'''
import random,itertools

deck= itertools.product(range(1,14),["spade","clube","hearts","dimonds"])

random.shuffle(deck)
print(deck)
for i in range(5):
    print(deck[i][0], "of", deck[i][1])
    '''

#program to display calander

'''import calendar

year =int(input("enter year: "))
month=int(input("enter month: "))

calendar=calendar.month(year,month)
print(calendar)
'''

#program to display fibonacci sequence using recursion
#(0,1,1,2,3,5,8,13)
#function call itself is called recursion
'''
def fibo(n):
    if n<=1:
        return n
    else:
        return fibo(n-1)+fibo(n-2)
n=int(input("enter a number here: "))
if n<=0:
    print("enter a positive number")
else:
    print("Fibonacci sequence")
    for i in range(n):
        print(fibo(i))
'''

#sum of natural numbers using recursion
#(positive numbers)
'''
def natur(n):
    if n<=1:
        return n
    else:
        return n+natur(n-1)
    
n=int(input("enter the number: "))
if n<=0:
    print("enter positive number")
else:
    print("the sum of natural nnumber upto given number is",natur(n))
'''

#factorial using recursion
'''
def fact(n):
    if n<=1:
        return n
    else:
        return n*fact(n-1)
    
n=int(input("enter the number: "))
if n<=0:
    print("Factorial of a number do not exist")
else:
    print("factorial of a number is",fact(n))
'''

#convert decimal to binary
'''
def convbin(n):
    if n>1:
        convbin(n//2)
    print(n%2,end="")

convbin(15)
'''

#program to add 2 matrices  
#for columns len(A[0]), for row len(A)
'''
A=[[1,5,8],
   [4,6,7],
   [7,2,3]]
B=[[4,5,6],
   [8,9,1],
   [3,5,6]]

result=[[0,0,0],
        [0,0,0],
        [0,0,0]]
for i in range(len(A)):
    for j in range(len(A[0])):
        result[i][j]=A[i][j]+B[i][j]

for r in result:
print(r)
'''

#program to Transpose a Matrix
#(using for loop) [1,2,3]
#                 [4,5,6] rows converted to column
#for column len(A[0]),for row len(A)
'''
A=[[1,2,3],
   [4,5,6]]

T=[[0,0],
   [0,0],
   [0,0]]
for i in range(len(A)):
    for j in range(len(A[0])):
        T[j][i]=A[i][j]
for i in T:
    print(i)
'''

#above program using list comprehension
'''
A=[[1,2,3],
   [4,5,6]]

T = [[A[j][i] for j in range(A)] for i in rane(len(A[0]))  ]]


for i in T:
    print(i)
'''

#python program to multiply two matrices
#result[i][j]+=A[i][k]+B[k][j]
'''   
A=[[1,2,3],
   [4,5,6],
   [7,8,9]]
B=[[1,2,1,1],
   [4,2,1,2],
   [6,3,4,1]]
result=[[0,0,0,0],
        [0,0,0,0],
        [0,0,0,0]]

for i in range(len(A)):
    for j in range(len(B[0])):
        for k in range(len(B)):
            result[i][j]+=A[i][k]*B[k][j]

for i in result:

    print(i)
'''

#program to check wether a string is palindrome or Not
#palindrome string are wow,madam,mam etc if reverse also same
#[::-1]
'''
a=input("enter a word here: ")
rev=a[::-1 ]

if a==rev:
    print("it is a palindrome number")
else:
    print("not palindrome number")
'''

#create punctuations from string
#using for loop, punctuations are (){}'""-_<>etc

#punc= '''!()-[]{};:'"\'<>./?@#$%^&*_~'''
'''string=input("enter anything here: ")
empty_str=""
for i in string:
    if i not in punc:
        empty_str=empty_str+i
print(empty_str)
'''
#program to sort words in alphabetic order
#using sting function and for loop
'''
a=input("enter something: ")
w=a.split()
print(w)
for i in range(len(w)):
    w[i]=w[i].lower()
w.sort()
print(w)
for i in w:
    print(i)
'''

#program to illustrate different set operations
#union:ex;(1,2),(3,4)=(1,2,3,4)=|
#intersection=(1,2),(2,3)=(2)=&
#diffusion=(1,2),(2,3)=(1)=-
#symmeetric diffusiion=(1,2),(2,3)=(1,3)=^
'''
A={6}
B={3,4,5,6,7,8}

print("the union is",A|B)
print("the intersection is",A&B)
print("the difference is",A-B)
print("the symmetric difference" ,A^B)
'''

#program to count the number of each vowel
#using dictnoriies
'''
a="Harry Potter and the Prisoner of Azkaban"
vowels="aeiou"
a=a.casefold(
print(a)
count={}.fromkeys(vowels,0)

for char in a:
    if char in count:
        count[char]+=1

print(count)
'''
#soluution2
#using list and dict
'''
a="Harry Potter and the Prisoner of Azkaban"
vowels="aeiou"
a=a.casefold()
count = {key:sum([1 for char in a if char ==key])for key in vowels}
print(count)
'''

#program to find size(resoluution) of image pil module

#import PIL
#from  PIL import Image
#img=PIL.Image.open("C:\Users\Dell\Desktop\youtube\the-geeta-1-chandresh-patel.png")
#idth,height=img.size
#print(width,"x",height) 


#python program to merg two dictionaries
#using | operator
'''
dict1={"john":89, "Lisa":99}
dict2={"Lisa":94, "peter":78}

print(dict1 | dict2)
'''

#solution 2
'''
dict1={"john":89, "Lisa":99}
dict2={"Lisa":94, "peter":78}

print({**dict1,**dict2})
'''

#solution3
'''
dict1={"john":89, "Lisa":99}
dict2={"Lisa":94, "peter":78}
dict3=dict2.copy()
dict3.update(dict1)
print(dict3)
'''

#program to access index of a list using for loop
#enumarate method
#enumarate[12,21,31,14]index 0,1,2,3
'''
l=[34,5,61,54,89]
for index, value in enumerate(l):
    print(index,"-",value)
'''

#not using enumarate method
'''
l=[34,5,61,54,89]
for index  in range(len(l)):
    value=l[index]
    print(index,value)
'''
#program to slice lists
'''
from math import gcd

def validList(x, n, a):
    valid = []  # Change this line to initialize 'valid' as an empty list
    
    for num in a:
        if gcd(x, num) == 1:
            valid.append(num)  # Append valid numbers to the list
    
    return valid

def main():
    x, n = map(int, input().split())
    a = list(map(int, input().split()))

    result = validList(x, n, a)
    print(*result)

if __name__ == "_main_":
    main()
    '''

#pprogram to slice list
#(start:stop:step)
'''
a=["Joe", "RACHEL","Monica","Phonebe","Ross","Chandler"]
print(a[4])
print(a[1:4])
print(a[::-1])
'''
#dictnories using for loop
'''
frinds={'Rachel':'Ross','Monica':'Chandler','Phoebe':'Joe'}
print(frinds)
for key,value in frinds.items():
    print(key,value)
'''
#program to sort a dictinary by value
#arks={"John":23, "Lisa":56, "sid":48}
#print(marks)
#dictnory bassed on values
'''
sv=sorted(marks.items(),key=lambda x:x[1])
print(sv)'''

#v=sorted(marks.values())
#print(v)

#check if a list is empty
#print(bool([12,4,5]))
'''
my_list=[12]
if not my_list:
    print("this list is empty")
    '''

#solution 2 using len
'''
lis=[12,13]
a=len(lis)
print(a)
if a==0:
    print("empty list")
else:
    print("not empty list")'''

#sloln3 using []
'''
lis=[12,13]
if lis==[]:
    print("empty")
else:
    print("not empty")
    '''

#program to catch multiple exceptions in one line
'''
sting=input("enter something herre:")
try:


    num=int(input("enter a number here: "))
    print(string+num)
except(ValueError,TypeError) as a:
    print(a)
'''

#python program to copy a file
#import shutil import copyfile
#copyfile()

#python program to concentrate 
#concatination list
#using+opertor
'''
l1 = [3,5,6,"s"]
l2=[4,4,5,"t"]
l12=l1+l2
print(l12)
'''
#unique values
#l1 = [3,5,6,"s"]
#l2=[4,4,5,"t"]
#l3=list(set(l1+l2))
#print(l3)

#using extend function
#l1.extend(l2)
#print(l1)

#program to check if a key is already present ina dictionary
'''
friends={"Rachel":"Ross","monca":"Chandler","Phone":"Joe"}

name= input("enter a key here: ")
if name in friends.keys():
    print("it is present")
'''

#program to parse a string to afloat or int
'''
string="12345"
print(type(string))
'''
#convert string to datetime
#soln1 datetime module
'''
from datetime import datetime
date ="Oct 14 1997 7:15AM"
print(type(date))

date_time=datetime.strptime(date,"%b %d %Y %I:%M%p ")
print(date_time)
'''
#6hr
#solution 2 using datetil module
'''from  dateutil import parser

dt=parser.parser("oct 14 1997 7:15AM")
print(dt)
print(type(dt))
'''
#prrogram to get the element of the list
'''
avg=["Ironman","Hulk","Thor","Vision"]
print(avg[::-1])
'''
#program to getsubtracting of a string
'''
a=input()
print(a[::2])
'''

#program to  get the last element of a list
#program to randomly select an element from the list
'''
num=input("enter number: ")

def floa(num):
    try:
        float(num)
        return True
    except:
        return False
    
print(floa(num))
'''

#program to check number in a strin
'''
import random
l=[2,5,"a","y",8,"p"]
ran=random.choice(l)
print(ran)
'''

#program to count occurrence of an items in a list
'''
num=[10,20,30,10,40,30,40]
con=num.count(20)
print(con)
'''
#6:30
