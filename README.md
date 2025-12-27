Features Required
➢ Random number generation
➢ User name input
➢ Guess validation with hints
➢ Attempt counting
➢ Score saving to file
➢ Scoreboard display
➢ Menu-driven program
Concepts to be Used
➢ Functions
➢ Loops
➢ Conditional statements
➢ Arrays & strings
➢ File handling
➢ Random numbers
Technology Used
➢ C Programming Language
➢ GCC / Turbo C Compiler
➢ Text File Handling (scores.txt)
➢ Standard C Libraries
Output
➢ Console-based number guessing game
➢ Scoreboard with player name and attempts
➢ Permanent data storage in file
1.Introduction
The Number Puzzle Game with Scoreboard is a console-based mini project developed 
using the C programming language. The game challenges the player to guess a randomly 
generated number within a given range. Each attempt is counted, and the final score 
(number of attempts) is saved permanently using file handling.
This project demonstrates the practical application of core C programming concepts 
such as random number generation, functions, loops, conditional statements, arrays, 
strings, and file handling. It is designed mainly for academic and learning purposes.
2.Objectives
➢ To design a simple interactive number guessing game in C
➢ To understand and implement random number generation using rand()
➢ To store player scores permanently using file handling
➢ To display a scoreboard from a file
➢ To improve logical thinking and problem-solving skills
➢ To demonstrate modular programming using functions
3.System Features
 3.1 Play Game
➢ The player enters their name
➢ The system generates a random number between 1 and 100
➢ The player guesses the number
➢ The program gives hints such as Too High or Too Low
➢ The game continues until the correct number is guessed
➢ Total attempts are counted.
3.2 Score Saving
➢ After the player guesses the correct number, their name and number of attempts are 
saved in a file
➢ File used: scores.txt
➢ Data is stored permanently even after the program exits
. 3.3 View Scoreboard
➢ Displays all saved player names with their attempts
➢ Reads data from the file and prints it in a formatted way
➢ Shows a scoreboard heading for better presentation
 3.4 Menu-Based System
The program provides a menu with the following options:
1. Play Game
2. View Scoreboard
3. Exit
4.Concepts & Technologies Used
 4.1 C Programming Concepts
➢ Functions – for modular design (playGame, saveScore, showScoreboard)
➢ Loops – for repeated guessing and menu handling
➢ Conditional Statements – to check guesses
➢ Arrays & Strings – to store player names
➢ Random Number Generation – using rand() and srand()
 4.2 File Handling
File handling is used to store and retrieve player scores.
➢ File Used:
• Scores.txt
➢ Operations:
• Append mode (“a”) to save scores
• Read mode (“r”) to display scoreboard
5.System Design
 5.1 Functional Modules
• playGame() – Handles the number guessing logic
• saveScore() – Saves player name and attempts into file
• showScoreboard() – Reads and displays saved scores
• main() – Controls menu and program flow
6. Workflow
➢ Program starts
➢ Menu is displayed
➢ User selects an option
➢ If Play Game is selected:
• Name is entered
• Random number is generated
• User guesses until correct
• Attempts are counted and saved
➢ If View Scoreboard is selected:
• Scores are read from file
• Displayed on screen
➢ Program exits on user choice
7. Random Number Generation
➢ The random number is generated using:
• Srand(time(0)) – to seed the random number generator
• Rand() % 100 + 1 – to generate numbers between 1 and 100
➢ This ensures different numbers are generated each time the program runs.
8. Sample Output (Console)
=== NUMBER PUZZLE GAME ===
1. Play Game
2. View Scoreboard
3. Exit
Enter your name: P.Sai Manikanta
I have selected a number between 1 and 100.
Enter your guess: 50
Too high!
Enter your guess: 25
Too low!
Enter your guess: 37
Correct! You guessed it in 3 attempts.
Scoreboard Output
🏆 SCOREBOARD 🏆
P.Sai Manikanta – 3 attempts
9. Advantages
➢ Simple and user-friendly
➢ Permanent score storage
➢ Improves logical and programming skills
➢ Demonstrates real-world use of file handling
10. Limitations
➢ Console-based (no GUI)
➢ No difficulty levels
➢ Scoreboard is not sorted
11. Future Enhancements
➢ Add difficulty levels (Easy, Medium, Hard)
➢ Sort scoreboard by least attempts
➢ Add date and time to scores
➢ Create a graphical user interface (GUI)
12. Conclusion
The Number Puzzle Game with Scoreboard is a simple yet effective C programming mini 
project. It provides hands-on experience with random numbers, file handling, and structured 
programming. This project is ideal for beginners and can be enhanced further with advanced 
features.
Project Name: Number Puzzle Game with Scoreboard Saved to File
Technology: C Programming Language
Type: Console-Based Mini Project
Team Members Names:
25A31A4357 P.Sai Manikanta 
25A31A4366 Y.V.D.Chaitanya
25A31A4355 N.B.Viswadeep
25A31A4316 K.Tejaswini
25A31A4302 D.Akshaya Sri
25A31A4303 Ch.Harshita
