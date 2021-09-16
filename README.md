# BMI-Calculator-
A simple calculator to calculate your BMI

#defining the weight, height, and BMI variables
weight = float(input('Tape your weight in Kg : '))

height = float(input('Tape your height in m : '))

BMI = int(weight/height**2)


#an alert informing you that you're underweight, overweight, or optimal using if-else loop
if BMI < 18:
    
    print (BMI)
    
    print ("You're Underweight")
    
elif  BMI >= 18 and BMI <= 24:
    
    print (BMI)
    
    print ("You're Optimal")
    
elif  BMI > 24:
    
    print (BMI)
    
    print ("You're Overweight")
    
else:
    
    print (BMI)
    
    
    
# Author : Mohamed El Mesghati
# Project name : BMI Calculator
# Programming language used : Python
#Date : Monday 13 September 2021, 15:20
