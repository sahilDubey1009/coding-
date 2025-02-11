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
     else: 
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
#    print("it is five or more digit number")
