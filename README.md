# Number Guessing Game with AI 🎯

## Description
This project is a number guessing game enhanced with machine learning. The AI attempts to predict the user's guessed number based on patterns in a randomly generated dataset. It uses a **Random Forest Classifier** to train on synthetic data and improve its predictions.

## Features
- Generates a dataset of random number pairs
- Implements feature engineering to improve prediction
- Trains a **Random Forest Classifier** model
- Predicts user guesses based on learned patterns
- Interactive gameplay where the AI attempts to guess your number

## Technologies Used
- Python
- Pandas
- Scikit-learn
- Random Forest Classifier

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/Kartikjattu/number-guessing-game.git
   cd number-guess-game
   ```
2. Install the required dependencies:
   ```bash
   pip install pandas scikit-learn
   ```
3. Run the game:
   ```bash
   python number_guessing_game.py
   ```

## How to Play
1. The AI will attempt to guess your number (1-10) based on its trained model.
2. A random number will be displayed.
3. The AI will predict your guessed number.
4. You provide feedback if the AI guessed correctly.
5. The game runs for 5 rounds or until the AI makes a correct prediction.

## Example Output
```
Let's play a number guessing game!
Think of a number between 1 and 10.
Random Number: 7
AI Predicts Your Guess: 4
Was the prediction correct? (yes/no): no
...
AI couldn't guess your number. Better luck next time!
```

## Contributing
Feel free to submit pull requests or suggestions to improve the game and AI predictions.

## License
This project is licensed under the MIT License.

