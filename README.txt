This was the first project for Computer Science II in the Fall of 2020 instructed by Dr. Louis Yu. 

The course first opened with a month long introduction to Assembly. More specifically, SLIM assembly language. 
SLIM was a simplified computer (standing for Super-Leadn Instruction Machine) that was utilized to show the basics of Assembly.

This project consisted of 4 tasks. 

Task 1: Write a program that reads in two numbers and then displays the sum of their squares. 

Task 2: Convert Python code to Assembly in a problem that is defines as the power-product where the program takes in the base and 
an exponent from the user, computes the power, and returns the solution. 

Task 3: Convert Python code to Assembly. The code for the Python formatting can be seen below:
def power (b,e):
    pow = 1
    while (e > 0):
        if ((e % 2) == 0)
            b = b * b
            e = e / 2
        else:
            pow = pow * b
            e = e - 1
    return pow


Task 4: Convert Python code to Assembly. The code for the Python formatting can be seen below:
def power (b, e):
    if (e == 0):
        return 1
    else:
        return b * power(b, e - 1)

The final part of this project was writing a report. This report analyzed the instruction count data for the procedures for the various tasks. 
