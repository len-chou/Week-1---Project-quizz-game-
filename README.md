# Week-1---Project-quizz-game-
Guess Who I Am

Guess Who I Am is a terminal-based guessing game written in Python. The program secretly picks a celebrity from a built-in list and reveals three clues about them, one at a time, growing more specific with each reveal. After every clue, the player gets one guess. Get it right, and the game moves on to celebrate the win before picking a new celebrity. Get it wrong on all three clues, and the game ends immediately, revealing who the mystery person was.

How it works
The game stores each celebrity as a dictionary entry, mapping their name to a list of three clues.
A random celebrity is selected from the remaining pool at the start of each round.
Clues are shown one at a time using a for loop, and the player's guess is checked against the answer (case-insensitive) after each one.
A correct guess ends the round early and the game continues to a new celebrity via an outer while loop.
Three incorrect guesses in a row end the game entirely — there's no restart or move to the next round.
Wrong guesses are tallied throughout, and the running total is reported as the final score if the player reaches the end of the celebrity list.
Why I built this

This project was built as a hands-on way to practice fundamental Python concepts, including:

Dictionaries for structured data storage
Lists for tracking game state
Loops (for and while) for controlling game flow
Conditionals for evaluating guesses
Functions for organizing the game logic into a single reusable entry point
Challenges along the way

Getting everything working smoothly wasn't without its bumps — a lot of small syntax errors, pieces of code that worked fine on their own but broke once combined, and a tricky bug caused by case-sensitive string comparisons that made correct guesses register as wrong.

Possible future improvements
Difficulty levels (fewer clues or a shorter guess limit)
Score tracking across multiple games with a leaderboard
A bigger cast of celebrities across more categories
