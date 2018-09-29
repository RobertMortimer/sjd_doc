# Week 2 - Flow control

## Basic flow control

Flow control is where we use logic statements such as 'if' & 'while' long with 'equals' or 'is greater than' to control what code in the program is to be run. We do the same in daily life:-

> "There is no milk in the fridge, nip down to the corner shop and get a carton of milk, if they have eggs get a dozen"

Old Joke

> "They had eggs, so I got the twelve cartons of milk"

The three flow control statements in Python are 'if', 'for' and 'while'. These are used along side tests to control the flow of a program.

```
If no milk in fridge then get more from shop
If shop has eggs get milk more milk
```

or

```
If no milk in fridge then get more from shop
If going to shops and number of eggs in fridge is less than 2 get eggs on same visit
```

Example \(in Python\)

```
# Ask for a number 
x = int(input("Ammout of milk in fridge: "))
# Is it less than 0?
# Is it equal to 0?
if x == 0:
  print('Get milk from shop')
e = int(input("Ammout of eggs in fridge: "))
if e < 6
  print('Get eggs while you are at the shop')
else
  print('We are OK for eggs')
elif x == 1:
  print('We may need to go to the shops for milk tomorrow')
else:
  print('We are OK for milk')
```

This is a simple example of flow control.

Exercise 2:1 if/else for 20 questions:

In the game of 20 questions the player gets 20 questions to go down a decision tree to identify the animal mineral or vegitable the persson answering the question is thinking of. In out case we are only going four questions deep \(Max 16 outcomes\)



