# ToolBox

###Input Output Interest Rate Calculator

def main():
  print("This program calculates the future value")
  print("of a 10-year investment.")
  
  principal = eval(input("Enter the initial principal"))
  apr = eval(input("Enter the annual interest rate:"))
  
  for i in range(10):
    principal = principal * (1 + apr)
    
  print("The value in 10 years is:", principal)
  
main()

###Loop & introduction

v_A = "Susan was studying in Germany."
v_B = "In Germany they use celsius instead of fahrenheit. "
v_c = "Susan created a program to convert celsius to fahrenheit"
print(_A, _B, _C)


def main():
  v_celsius = 0
  for x in range(5):
    v_celsius = eval(input("What is the Celsius temperature?"))
    fahrenheit = 9/5 * v_celsius + 32
    print(x+1, "-) The temperature is", fahrenheit, "degrees Fahrenheit.")
  
  
main()

###User input 

def main():
  print("This program calculates the future value")
  
  years = eval(input("Enter the number of years:"))
  principal = eval(input("Enter the initial principal:"))
  apr = eval(input("Enter the annual interest rate:"))
  
  for i in range(10):
    principal = principal * (1 + apr)
    
  print("The value in years is:", principal)
  
main()


###Ounces to Milliliters

v_A = "In this program we are converting ounces to milileters."
print(v_A,)


def main():
  ounces = eval(input("Enter amount of ounces:"))
  milileters = 30 * ounces
  print(milileters, " milileters")
  
main()

###Adding a space

greeting = "G'Day" + ' ' + "mate" 
print(greeting)

###Sentences stuff

name = "k"
description = "e"
year = "l"

sentence = name + ' a ' + description + ' b ' + year
print(sentence)

###Area

v_width = eval(input("What is the width?"))
v_height = eval(input("What is height?"))
area = v_width * v_height
print("The area is", area ,"square feet.")




###Perimeter

v_width1 = eval(input("What is the length of side 1?"))
v_height1 = eval(input("What is the length of side 2?"))
v_width2 = eval(input("What is the length of side 3?"))
v_height2 = eval(input("What is the length of side 4?"))
perimeter = v_width1 +  v_height1 + v_width2 + v_height2
print("The perimeter is", perimeter ,"feet.")

###Circumference
v_radius = eval(input("What is the radius?"))
pi = 3.14
circumference = 2 * pi * v_radius
print("The circumference is", circumference ,"feet.")

###Average of 3 numbers

v_heartRate1 = eval(input("What is your morning heart rate?"))
v_heartRate2 = eval(input("What is your afternoon heart rate?"))
v_heartRate3 = eval(input("What is your evening heart rate?"))
averageHR = print((v_heartRate1 + v_heartRate2 + v_heartRate3) / 3)

###Fahrenheit to Celsius

def main():
  v_farenheight = eval(input("What is the Farenheight temperature?"))
  celsius = (v_farenheight - 32)* (5 / 9)
  print(" The temperature is", celsius , "degrees Celsius.")
  
main()

###Average answer that equals int not float

v_A = 1.2
v_B = 10.5
v_C = 11.6
addedHR = print((v_A + v_B + v_C) // 3)

###Slice function

v_string = "I like pink."

print(v_string[0:11:3])

###Count function on strings

v_string = "Live Laugh Love"
print(v_string.count("Laugh", 0, 13)) 

###Number and string

def main():
    v_months = "JanFebMarAprMayJunJulAugSepOctNov"
    v_A = int(input("Enter a month number (1-12):"))
    pos = (v_A-1) * 3
    v_monthABVR = v_months[pos:pos+3]
    print("The month abbreviation is", v_monthABVR + ".")
main()


