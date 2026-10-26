# fibonacci
this is a  python program to find any fibonacci series for any number

# Fibonacci Series Generator

A Python program that prints the first n numbers of the Fibonacci sequence.

## Description

`fibonacci.py` prompts the user for the number of terms and prints the Fibonacci series as a list. Each number is the sum of the two before it, starting from 0 and 1.

## Features

- Generates the first n Fibonacci numbers
- Iterative implementation (no recursion depth limits)
- Supports very large terms using Python's built-in big integers
- No external dependencies

## Requirements

- Python 3

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
   ```

2. Navigate to the project directory:

   ```bash
   cd <your-repo-name>
   ```

No additional packages need to be installed.

## Usage

Run the script from your terminal:

```bash
python fibonacci.py
```

Enter a whole number when prompted. The program prints the series.

## Example

```
$ python fibonacci.py
How many terms? 10
[0, 1, 1, 2, 3, 5, 8, 13, 21, 34]
```

```
$ python fibonacci.py
How many terms? 0
[]
```

## Project Structure

```
.
├── fibonacci.py
├── README.md
└── audit.md
```
