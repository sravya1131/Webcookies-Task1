
Name : MADASU SRAVYA
Company: CODTECH IT SOLUTIONS 
Domain: Java programming 
Durartion: 25th May 2024 to 25th June 2024
![Screenshot (9)](https://github.com/sravya1131/Webcookies-Task1/assets/112858180/d46825ac-d6db-4f6d-bd15-f20285d60134)


Project Review: Number Guessing Game
Overview
The number guessing game is a simple yet engaging application where the program selects a random number within a user-defined range, and the player tries to guess it. The game provides feedback on whether the guess is too high, too low, or correct. It also includes features for setting the range, limiting the number of attempts, and displaying the player's performance at the end.

Features
Setting the Range of Numbers:

The user inputs the minimum and maximum values for the range.
Ensures flexibility and replayability by allowing different ranges.
Random Number Generation:

The program uses java.util.Random to generate a random number within the specified range.
Ensures the game remains unpredictable and fair.
Limiting the Number of Attempts:

The user specifies the number of attempts they are allowed.
Adds a challenge element to the game and prevents infinite guessing.
Feedback on Guesses:

The program provides immediate feedback if the guess is too high, too low, or correct.
Enhances the user experience by guiding the player towards the correct answer.
Displaying User's Performance:

The program displays a message indicating whether the user guessed the number correctly and how many attempts it took, or if they ran out of attempts.
Provides closure to the game and encourages replay.
Code Structure
Main Method:

Handles user input for setting the range and number of attempts.
Manages the game loop where guesses are made and feedback is given.
Displays the final performance message.
Random Number Generation:

Utilizes Random.nextInt() for generating a random number within the specified range.
Ensures the generated number is within the user-defined bounds.
User Input and Feedback:

Uses Scanner for reading user inputs.
Implements a loop for handling multiple guesses and providing feedback.
Performance Display:

Determines if the user guessed the number correctly within the allowed attempts.
Displays an appropriate message based on the outcome.
Strengths
User-Friendly Interface:
Simple prompts and clear feedback make the game easy to understand and play.
Modular Design:
Separation of concerns with distinct sections for input handling, game logic, and feedback.
Flexibility:
Allows the user to set different ranges and attempt limits, enhancing replay value.
Clear Feedback:
Immediate and accurate feedback on guesses keeps the player informed and engaged.
Potential Improvements
Input Validation:

Add input validation to ensure the user enters valid numbers for the range and attempts.
Handle non-integer inputs gracefully to prevent crashes.
Enhanced User Experience:

Add a welcome message and instructions at the beginning of the game.
Consider allowing the player to play multiple rounds without restarting the program.
Code Optimization:

Encapsulate game logic into separate methods or classes for better readability and maintainability.
Advanced Features:

Implement difficulty levels that adjust the range and number of attempts automatically.
Add a scoring system to track the player's performance over multiple games.
Conclusion
The number guessing game is a well-implemented project that provides a fun and interactive experience for users. It effectively uses basic Java constructs and offers flexibility through user-defined settings. With some minor enhancements, it can become even more robust and user-friendly. Overall, it demonstrates a good understanding of programming principles and user interaction design.
