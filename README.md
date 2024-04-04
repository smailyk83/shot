# shot
import random

# Generate a random number between 1 and 10
random_number = random.randint(1, 10)

# Ask the user to guess the number
guess = int(input("Guess a number between 1 and 10: "))

# Check if the guess is correct
if guess == random_number:
    print("Congratulations! You guessed the correct number.")
else:
    print("Sorry, the correct number was " + str(random_number) + ". Better luck next time!")
