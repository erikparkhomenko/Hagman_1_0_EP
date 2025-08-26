# Hagman_1_0_EP
This is my attempt at coding a basic version of the hangman game in Python. I used it as a practice imports, for and while loops, and if statements. Feel free to check it out :)

Welcome to the classic Hangman game! This Python implementation provides a fun and interactive way to test your vocabulary skills.

How to Run the Game
Clone the Repository: First, you need to clone the repository containing the game files to your local machine.

Bash
git clone https://github.com/yourusername/hangman-game.git
Navigate to the Project Directory: Change into the directory where the project is located.

Bash
cd hangman-game
Install Dependencies (if any): The game should work out-of-the-box, but if it requires any additional packages, you can install them using pip.

Bash
pip install -r requirements.txt
Note: If there is no requirements.txt, this step may be skipped.

Run the Game: Execute the game script using Python.

Bash
python Hangman_1.0.py
Gameplay
Objective
The objective of the game is to guess a randomly selected word from a predefined list by guessing individual letters. You have 6 lives, and each incorrect guess reduces your remaining lives.

Controls
Guess a Letter: Type a letter when prompted and press Enter.
View Word Progress: The game will display the current state of the word with correctly guessed letters filled in and underscores for unguessed letters.
Game End: The game ends when you either guess all the letters correctly or run out of lives.
Customization
Adding Words
You can add more words to play with! Simply edit the word_list in the 
hangman_words.py
 file. Each word should be a string and separated by commas.

Python

# hangman_words.py
word_list = [
    "apple",
    "banana",
    # Add more words here...
]
Changing Game Art
The game's visual art is defined in the 
hangman_art.py
 file. You can replace or modify the ASCII art to change the look of the game.

Python

# hangman_art.py
stages = [
    r"""
      +---+
      |   |
          |
          |
          |
          |
    =======
    """,
    # Add more stages here...
]

logo = r""" 
 _                                             
| |                                            
| |__   __ _ _ __   __ _ _ __ ___   __ _ _ __  
| '_ \ / _` | '_ \ / _` | '_ ` _ \ / _` | '_ \ 
| | | | (_| | | | | (_| | | | | | | (_| | | | |
|_| |_|\__,_|_| |_|\__, |_| |_| |_|\__,_|_| |_|
                    __/ |                      
                   |___/    """
Contributing
Contributions are welcome! Feel free to submit pull requests or open issues for bug reports and feature suggestions.

License
The game is released under the MIT License. See LICENSE for more details.

Enjoy playing Hangman!
