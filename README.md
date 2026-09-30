# C Typing Speed Tester

A lightweight command-line typing test written in C. The program prompts the user to type a predefined sentence, measures the time required to complete the input, and calculates both typing speed and character accuracy.

## Features

- Measures typing time using `gettimeofday()` with microsecond precision
- Calculates typing speed in words per minute (WPM)
- Calculates character-level typing accuracy
- Counts words from user input
- Demonstrates C string manipulation and standard input handling
- Uses basic boolean state tracking to identify individual words

## Concepts Demonstrated

This project was built as a hands-on exercise in C programming and low-level programming concepts, including:

- Functions and return values
- Character arrays and C strings
- String length and manipulation with `strlen()`
- Standard input with `fgets()`
- Boolean state management
- Time measurement with `struct timeval`
- Microsecond timestamp calculations
- Basic performance measurement
- Type casting and numerical calculations
- Command-line program structure

## How It Works

The program displays the following phrase:

> The quick brown fox jumps over the lazy dog

The user types the phrase and presses Enter. The program records the start and end timestamps, calculates the elapsed time, counts the number of words entered, and compares the user's input against the reference text.

The final output includes:

- The user's submitted text
- Typing speed in words per minute
- Typing accuracy as a percentage

## Example

```text
Type "The quick brown fox jumps over the lazy dog"

The quick brown fox jumps over the lazy dog

User typed "The quick brown fox jumps over the lazy dog"
Typing speed: XX.XX words/min
Accuracy: 100.00%
