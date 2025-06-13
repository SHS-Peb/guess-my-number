# Guess My Number

## Description

Welcome to the Number Guessing Game! This simple console application challenges the player to guess a randomly generated number between 1 and 100. It's a fun way to practice basic C++ concepts like loops, conditionals, user input, and random number generation.

## How to Play

1. Run the program.
2. The computer will secretly pick a number between 1 and 100.
3. Enter your guesses when prompted.
4. After each guess, you'll be told if your guess was too low, too high, or correct.
5. Keep guessing until you find the correct number.
6. When you guess correctly, the program will display how many attempts you took.

## Features

- Random number generation with `std::rand()`
- Simple user input validation
- Tracks the number of attempts
- Provides friendly feedback after each guess

## Getting Started

### Prerequisites

- A C++ compiler such as `g++`, `clang++`, or MSVC

### Compiling the Code

To compile using `g++`, run: `g++ -o guessing_game guessing_game.cpp`

### Running the Program

Run the compiled executable:
`./guessing_game`
