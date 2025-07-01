# Guess the Number Game in Rust

A simple command-line number guessing game written in Rust.

## Description

This is a classic "Guess the Number" game where the program generates a random number between 1 and 100, and the player tries to guess it. The game provides feedback on whether the guess was too high or too low, and congratulates the player when they guess correctly.

## Features

- Random number generation between 1 and 100
- Colored output for better visual feedback
- Input validation (only accepts numeric input)
- Immediate feedback on each guess
- Win detection and game termination

## Requirements

- Rust installed (version 1.70.0 or later recommended)
- Cargo (Rust's package manager)

## Installation

1. Clone this repository or copy the code into a new Rust project
2. Add the following dependencies to your `Cargo.toml`:

```toml
[dependencies]
colored = "2.0.0"
rand = "0.8.5"
```

3. Run `cargo build` to install dependencies

## Usage

1. Compile and run the program:
   ```bash
   cargo run
   ```

2. Follow the on-screen instructions:
   - The program will generate a random number
   - Enter your guess when prompted
   - The program will tell you if your guess is too high or too low
   - Continue guessing until you find the correct number

## Note

The current implementation shows the secret number at the start (for debugging purposes).
```rust
println!("The secret number is: {secret_number}");
```
