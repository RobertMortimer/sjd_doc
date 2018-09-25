# Week 2 : An introduction to Python

## Flow control

Flow control is the way a program takes diffrent routes through the code depending on the input. This is done based on logic statements.

My partner told me

> "Go to the corner shop and get a carton of milk, if they have eggs get 6."
>
> "They had eggs so I got the 6 cartons of milk"

Or in Python

`
x = int(input("Please enter an integer: "))
if x < 0:
x = 0
print('Negative changed to zero')
elif x == 0:
print('Zero')
elif x == 1: 
print('Single')
else:
print('More')
`

