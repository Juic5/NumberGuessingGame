Number Guessing Game 🎯
Overview
This is a simple Java console application where the player must guess a randomly generated number between 1 and 10. The player has three attempts to guess correctly. After each guess, the program provides feedback, and at the end of the attempts, the correct number is revealed if not guessed.
Features
Generates a random number between 1 and 10 using Java’s Random class.
Limits the player to 3 attempts.
Provides feedback after each guess:
✅ Success message if the guess is correct.
❌ Wrong guess message with encouragement to try again.
Displays the correct answer if the player fails to guess within 3 attempts.
How to Run
Make sure you have Java JDK (version 8 or above) installed.
Save the program in a file named NumberGuessingGame.java under the day7 package.
Compile the code:
javac day7/NumberGuessingGame.java
Run the program:
java day7.NumberGuessingGame
Sample Gameplay
Welcome to the Number Guessing Game!
Guess a number between 1 and 10
You have 3 attempts. Good luck

Attempt 1: Enter your guess:
5
X Wrong guess
Try again!

Attempt 2: Enter your guess:
3
X Wrong guess
Try again!

Attempt 3: Enter your guess:
7
Congratulations! You guessed the correct number
Or, if all attempts are wrong:
You've used all attempts. The correct number was: 9
Code Highlights
Uses Scanner for user input.
Uses Random for number generation.
Implements a for loop to track attempts.
Closes the Scanner at the end to prevent resource leaks.
Possible Enhancements
Allow the user to select the difficulty level (change the number range and attempts).
Keep track of scores across multiple rounds.
Provide hints (e.g., "Too High" or "Too Low").
Add input validation to handle non-integer entries.
