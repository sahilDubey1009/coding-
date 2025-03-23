###typecastinginpython###
a=3
print(a,type(a)
b=float(a)
print(b,type(b)

##int to complex###
a=33
print(a,type(a)
b=complex(a)
print(b,type(b)


#if statement
marks=92
if marks>=90:
    print('you will get mobile phone')
   print ("thank you")
 if else
  
  marks  =  87
if marks >=90:
     print("you will get a phone")     
     
         print("no phone for 1 week")
         print("thank you")

         
if elif statement
marks=55
if marks>=90:
    print("you will go for a trip")
elif marks>=80 and marks<=90:
    print('you will get a phone')
else:
    print('no phone till one month')



    marks = 97
if marks>=90:
    print("you will go to trip")
elif marks >=80 and marks <90:
        print("you will get a new phone")
elif marks >=70 and marks <80:
            print("you will get a book")
else:
                print("you have to give your phn back")

#write a program to check whether a passed letter is vowel or not

letter=input("enter a number here")
if letter in "a e i o u ":
    print ("it is a vowel")
else:
    print("it is not a vowel")

#for loop
for i in range (1,6):
    print ("hello brother")



#write a program to check if a number is a single digit number or #upto 5 digit number

num = int(input("enter a number here upto 5 digit: "))
if num>=0 and num <=9:
    print("it is a single digit number")
elif num>=10 and num <=99:
    print("it is a double digit number")
elif num>=100 and num <=999:
    print("it is a triple digit number")
elif num>1000 and num <=9999:
    print("it is a four digit number")
else:
    print("it is five or more digit number")


#swap case 
a=30
b=40
a,b=b,a
print(b)
print(a)

o="sahil"
b="dubey"
o,b=b,o
print(o)
print(b)

#area of square 
side = float(input("Enter the length of a side of the square: "))
area = side**2
print(f"The area of the square is: area")

#area of rectangle

length=float(input("enter the length"))
width =float(input("enter the width"))
area=length*width
print("the area of rectangle, :area")

#area of rectangle

length=float(input("enter the length"))
width =float(input("enter the width"))
area=length*width
print("the area of rectangle, :area")

#area of circle

radius = float(input("enter the radius"))
area=radius**2
print("enter the area of circle,:area")


#logical operator
a = 10
b = 5
c = 20

print(a > b and c > a)

print(a > b or c < a)

print(not (a > b))

#and logical operator
a=10
b=5
c=20
print(a>b and c>a)#both should be true
#or logical operator
a=66
b=8
c=77
print(a>b or c<a)#only one can be true
#not logical operator
a=99
b=55
c=9
print(not(a>b))#shows opposite result#shows true if it is false

#swap using 3rd variable
a=10
b=20

print("Berfore Swapping: A:",a," B:",b)
temp=a #temp=10
a=b  #a=20
b=temp  #b=10
print("After Swapping: A:",a," B:",b)

#lists in python 
#List items are ordered, changeable, and allow duplicate value
#When we say that lists are ordered, it means that the items have a defined order, and that order will not change.

#If you add new items to a list, the new items will be placed at the end of the list.

a= ["apple", "banana", "cherry"]
print(a)
#What will be the result of the following syntax:
mylist = ['apple', 'banana', 'cherry']
print(mylist[1])
#output
banana
#What will be the result of the following syntax:
mylist = ['apple', 'banana', 'banana', 'cherry']
print(mylist[2])
#output
banana
#Select the correct function for returning the number of items in a list:

thislist = ['apple', 'banana', 'cherry']
print(len(thislist))

#PYTHON ACCESS LISTS

#What will be the result of the following syntax:
mylist = ['apple', 'banana', 'cherry']
print(mylist[-1])
#output
cherry

#Print the second item in the fruits list.

fruits = ["apple", "banana", "cherry"]
print(fruits[1])

#What will be the result of the following syntax:
mylist = ['apple', 'banana', 'cherry', 'orange', 'kiwi']
print(mylist[1:4])
#output
['banana', 'cherry', 'orange']

#Use a range of indexes to print the third, fourth, and fifth item in the list.


fruits = ["apple", "banana", "cherry", "orange", "kiwi", "melon", "mango"]
print(fruits[2:5])
#output
['cherry', 'orange', 'kiwi']

#PYTHON CHANGE LISTS

#What will be the result of the following syntax:
mylist = ['apple', 'banana', 'cherry']
mylist[0] = 'kiwi'
print(mylist[1])
#output
banana

#What will be the result of the following syntax:
mylist = ['apple', 'banana', 'cherry']
mylist[1:2] = ['kiwi', 'mango']
print(mylist[2])
#output
mango
#if else statements
num = int(input("Enter a number: "))
if num % 2 == 0:
    print("Even number")
else:
    print("Odd number")

    age = int(input("Enter your age: "))
if age >= 18:
    print("Eligible to vote")
else:
    print("Not eligible to vote")

    #oops 
    #class/object
   # Create an object of MyClass called p1:
class MyClass:
  x = 5
p1=MyClass()

# Use the p1 object to print the value of x:
class MyClass:
  x = 5

p1 = MyClass()
print(p1.x)

# Insert the missing parts to make the code return: John(36):
class Person:
    def __init__(self, name, age):
        self.name = name
        self.age = age

    def __str__(self):
        return f'{self.name}({self.age}):'

# Example usage:
p1 = Person('John', 36)
print(p1)

# When the class object is represented as a string, there is a function that controls what should be returned, which one?
_str__()

# What is a correct syntax for deleting an object named person in Python?
del person

# if else 
What will be the result of the following code:
x = 5
y = 8
if x > y:
  print('Hello')
else:
  print('Welcome')
  #o/p
  welcome
  
 # Print "Hello World" if a is greater than b.
a = 50
b = 10
if a > b:

  print("Hello World")

#  Print "Hello World" if a is not equal to b.
a = 50
b = 10
if a != b:

  print("Hello World")

# Print "Yes" if a is equal to b, otherwise print "No".

a = 50
b = 10
if a == b:
  print("Yes")
else:
  print("No")

#  Print "1" if a is equal to b, print "2" if a is greater than b, otherwise print "3".
a = 50
b = 10
if a == b :

  print("1")
elif  a > b :
 
  print("2")
else:

  print("3")
# create a class named person,use __init__() function to assin value for name , age
 class Person:
  def __init__(self, name, age):
    self.name = name
    self.age = age

p1 = Person("John", 36)

print(p1.name)
print(p1.age)

# OUTPUT
JOHN , 36
