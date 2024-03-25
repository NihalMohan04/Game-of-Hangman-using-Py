# Hangman Game Project

This project is a 3rd Semester Python Programming Lab creation. It's a Hangman game that uses Tkinter for the GUI, offering a fun and interactive way for users to play Hangman right from their desktop. The game selects a word at random from a list loaded from a file and the player guesses letters to reveal the word, with a limited number of incorrect guesses before the game is over.

## Features

- Simple GUI using Tkinter
- Word list loaded from a file
- Dynamic guessing and display of correct/incorrect letters
- Limited guesses with visual hangman progression
- Reset and new game functionality


## Running the Application

To run this application, ensure you have Python and Tkinter installed on your system. Save the script as `hangman.py`, and run it using:

```bash
python hangman.py
```

## Dependencies

- Python 3.7 and above
- Tkinter module
- A text file named `commonword.txt` containing words for the game, each on a new line. (Attached in the Repository for reference)

Make sure to place the `commonword.txt` in the same directory as your `hangman.py` script or modify the path in the script accordingly.


![GitHub Image](/images/won.png)
![GitHub Image](/images/lost.png)
![GitHub Image](/images/single.png)
