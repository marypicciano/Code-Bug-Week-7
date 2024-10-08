# Code-Bug-Week-7
#CODE BUG WEEK 7

def greet(name): #set up function to accpet a name withe the name parameter
    print("Hello, " + name + "!")

def add_numbers(a, b): #set up function for number addition
    return(a+ b)
   
#MAIN stuff and variables

name = input("Enter your name:") #accept the name as a string
greet(name) #call the greet function

num1 = int(input("Enter the first number:")) #accepting numbers
num2 = int(input("Enter the second number:")) #accepting numbers covert to integer

result = add_numbers(num1, num2)
print("The sum is: " + str(result)) #either convert back to string or replace the + with a comma
