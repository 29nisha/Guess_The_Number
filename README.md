# Guess_The_Number
Hii, I am Nisha  
Guess The Number is a very easy game which is made using python code.

 ![image](https://github.com/user-attachments/assets/fceefab9-06f5-4101-8d97-47dde78f4a75)

# Peoject Description:

- A Simple Number Guessing Game in Python. A Fun and Interactive Python Game
- This project creates a simple number guessing game in Python, where the user has to guess a randomly generated number.
- The game is designed to practice fundamental Python concepts like random number generation, user input, and conditional logic.
- The project aims to provide a fun and interactive way to learn Python programming skills.

# This Project involves the following steps:

 Step 1: Random Number Generation:
         Generate a random number using Python's random module.
         Define the range of the random number, e.g., between 1 and 100.

Step 2: User Input: Use Python's input function to get a number input from the user.
          Prompt the user to enter a number within the defined range.

Step 3: Number Comparison:
          Compare the user's input number with the generated random number.
          If the user's number matches the random number, congratulate the user.

Step 4: Hint Generation:
         If the user's number does not match the random number, provide a hint.
         The hint can be, for example, "Your number is too high" or "Your number is too low."

Step 5: Repeat Gameplay:
         Ask the user if they want to play again.
          If the user responds affirmatively, restart the game.

Step 6: Game Over:
          When the user chooses to stop playing, end the game and thank the user.


   import random
num=random.randint(0,50)
print("you have 5 chance to guess the number")
chance=0
while True:
if (chance==5):
print("You Lost The Game")
else:
user=int(input("Guess The Number Between 0 to 50:"))
if (user<num):
print("Try Agin!","Your Guess Was Too High")
chance+=1
if (user>num):
print("Try Agin","Your Guess Was Too Small")
chance+=1
if(user==num):
print("Congratulations","you guessed the number")
chance+=1
if (user!=num):
print("Try Agin")
if(chance==5):
print('Better Luck Next Time')
break
you have 5 chance to guess the number
Guess The Number Between 0 to 50:45
Try Agin Your Guess Was Too Small
Try Agin
Guess The Number Between 0 to 50:34
Try Agin! Your Guess Was Too High
Try Agin
Guess The Number Between 0 to 50:25
Try Agin! Your Guess Was Too High
Try Agin
Guess The Number Between 0 to 50:54
Try Agin Your Guess Was Too Small
Try Agin
Guess The Number Between 0 to 50:23
Try Agin! Your Guess Was Too High
Try Agin
Better Luck Next Tim


   



