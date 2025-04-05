 Hangman Game  

A simple command-line Hangman game written in Python. The objective of the game is to guess the hidden word by suggesting letters before running out of attempts.  

 Features  
- Random word selection from a predefined list  
- ASCII-based Hangman visuals  
- Single-player mode  
- Option to play again after finishing a round  
- Input validation for incorrect or repeated guesses  

## How to Play  
1. The game selects a random word.  
2. Players guess one letter at a time.  
3. If the guessed letter is correct, it is revealed in the word.  
4. If the guessed letter is incorrect, a part of the Hangman is drawn.  
5. The game ends when either:  
   - The player correctly guesses the word.  
   - The Hangman is fully drawn (5 incorrect guesses).  

 Installation  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/hangman-game.git  
   cd hangman-game  
   ```  
2. Run the Python script:  
   ```bash
   python hangman.py  
   ```  

 Example Gameplay  
```
Welcome to Hangman game  
Enter your name: John  
Hello John! Best of Luck!  
The game is about to start! Let's play Hangman!  

This is the Hangman Word: _ _ _ _ _  
Enter your guess: a  
_ a _ _ _  

Enter your guess: e  
Wrong guess. 4 guesses remaining.  
```

 Requirements  
- Python 3.x  

 Contributing  
Contributions are welcome! Feel free to fork the repository and submit pull requests with improvements.  

 License  
This project is licensed under the MIT License.  
