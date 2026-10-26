# fibonacci
this is a  python program to find any fibonacci series for any number
# Fibonacci Series Generator

A simple Python program that generates the first n numbers of the Fibonacci sequence.

## Description

This project provides a lightweight command-line tool for generating the Fibonacci series. The `fibonacci.py` script prompts the user for the number of terms, validates the input, and prints the series as a list. It is a clean, beginner-friendly example of iterative problem solving in Python.

Each number in the Fibonacci sequence is the sum of the two before it, starting from 0 and 1:

```
0, 1, 1, 2, 3, 5, 8, 13, 21, 34, ...
```

## Features

- Generates the first n Fibonacci numbers
- Iterative implementation (no recursion depth limits)
- Input validation for invalid and negative values
- Supports very large terms using Python's built-in big integers
- Importable as a module
- No external dependencies

## Requirements

- Python 3.6 or higher

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

Enter the number of terms when prompted.

To use the function in your own code:

```python
from fibonacci import fibonacci

print(fibonacci(10))  # [0, 1, 1, 2, 3, 5, 8, 13, 21, 34]
```

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
└── LICENSE
```

## Contributing

Contributions, issues, and feature requests are welcome. Feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
