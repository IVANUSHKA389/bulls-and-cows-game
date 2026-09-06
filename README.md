# Bulls and Cows Game

Console implementation of the classic Bulls and Cows game written in Python.

## About the project

Bulls and Cows is a number guessing game.

The player must guess a four-digit number with non-repeating digits.

After each attempt, the program shows:

- Bulls — correct digits in the correct position
- Cows — correct digits in the wrong position

The game continues until the number is guessed correctly.

## Features

- Four-digit number guessing
- Non-repeating digit validation
- Two game modes
- Player can choose the secret number
- Computer can generate a random secret number
- Bulls and cows calculation
- Attempt counter
- Game duration tracking
- Multiple game sessions

## Technologies

- Python
- datetime
- random

## Game rules

The secret number contains four different digits.

Example:

```text
Secret number: 1234
Attempt:       1532
```

In this example:

- `1` is a Bull because it is in the correct position
- `2` and `3` are Cows because they exist in the secret number but are in different positions

The goal is to guess all four digits in their correct positions.

## Project structure

```text
bulls-and-cows-game/
├── main.py
├── README.md
└── .gitignore
```

## Installation

Clone the repository:

```bash
git clone https://github.com/ivanivan220906-design/bulls-and-cows-game.git
```

Go to the project folder:

```bash
cd bulls-and-cows-game
```

Run the game:

```bash
python main.py
```

No additional libraries are required.

## Purpose

This project was created to practice basic Python programming concepts:

- variables
- conditions
- loops
- lists
- sets
- functions and program logic
- input validation
- random number generation
- working with date and time

## Author

Ivan Kornaukhov

Business Informatics student.
