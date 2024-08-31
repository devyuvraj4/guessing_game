# Guessing Game

This is a command-line based guessing game implemented in Rust. The game generates a random number, and the player has to guess the correct number within a certain range. The game provides feedback on whether the guessed number is too high, too low, or correct.

## Features

- Random number generation
- Input validation
- Looping until the correct guess is made
- Feedback on whether the guess was too high or too low

## Getting Started

### Prerequisites

- [Rust](https://www.rust-lang.org/tools/install) installed on your machine.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/devyuvraj4/guessing_game.git
   cd guessing-game
   ```

2. Build the project:

    ```bash Copy code
        cargo build
    ```    
3. Run the game:

    ```bash Copy code
    cargo run
    ```
## How to Play

    The game will prompt you to input a guess within a specified range (e.g., 1 to 100).
    Type your guess and press Enter.
    The game will tell you if your guess was too high, too low, or correct.
    Continue guessing until you find the correct number.
    The game will congratulate you once you've guessed the correct number.
    
## Example Gameplay

    ```css Copy code
    Guess the number!
    Please input your guess.
    > 50
    Too small!
    Please input your guess.
    > 75
    Too big!
    Please input your guess.
    > 63
    You guessed it!
    ```

### Contributing
    If you would like to contribute to this project, feel free to fork the repository and submit a pull request. Please make sure to write tests and document your code.

### License
    This project is licensed under the MIT License - see the LICENSE file for details.