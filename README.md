# Hello Cargo — Rust Guessing Game

A simple **command-line number guessing game** written in [Rust](https://www.rust-lang.org/).
This project follows the *Guessing Game* example from *The Rust Programming Language* book and demonstrates Rust fundamentals like user input, loops, and pattern matching.

## Overview

The program randomly chooses a number between **1 and 100**, and the player tries to guess it.
After each attempt, the game reports whether the guess is **too small**, **too big**, or **correct** — looping until the correct number is guessed.

## Features

- Random number generation using the `rand` crate
- User input handling via command line
- Error handling for non-numeric inputs
- Continuous gameplay until the correct answer

## Getting Started

### Prerequisites

- [Rust toolchain](https://www.rust-lang.org/tools/install) (includes Cargo)
- Basic command-line familiarity

### Running the Game

```bash
# Clone the repository
git clone https://github.com/yourusername/hello_cargo.git
cd hello_cargo

# Run the game
cargo run
```

### How to Play

1. The game will prompt you to guess a number
2. Enter your guess (between 1-100) and press Enter
3. Receive feedback on whether your guess was too high, too low, or correct
4. Keep guessing until you find the correct number!

## Project Structure

- `src/main.rs` - The main game logic
- `Cargo.toml` - Project dependencies and metadata

## Built With

- [Rust](https://www.rust-lang.org/) - The programming language used
- [rand](https://crates.io/crates/rand) - For random number generation