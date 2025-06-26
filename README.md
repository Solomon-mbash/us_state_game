# US States Game

This is a simple game where you have to guess the names of US states. The game uses the Turtle graphics module to display a map of the US, and you type in your guesses. If your guess is correct, the state's name will appear on the map.

## How to Play

1. Run the `main.py` file.
2. A map of the US will appear, along with a prompt asking for a state name.
3. Type in the name of a US state and press Enter.
4. If your guess is correct, the state's name will be written on the map.
5. Continue guessing until you have named all 50 states, or type "Exit" to end the game.
6. If you exit, a `states_to_learn.csv` file will be created with the states you missed.

## Requirements

- Python 3
- `turtle` module (built-in)
- `pandas` library (`pip install pandas`)

## Files

- `main.py`: The main game logic.
- `50_states.csv`: Contains the names and coordinates of the US states.
- `blank_states_img.gif`: The image of the US map.
- `states_to_learn.csv`: (Generated after exiting the game) Contains the list of states you didn't guess.