# README Claims Audit

Audit of the claims in `README.md` against the actual code in `fibonacci.py`.

| # | Claim | Verdict | Evidence from code |
|---|---|---|---|
| 1 | Generates the first n Fibonacci numbers | Supported | `for _ in range(n): series.append(a); a, b = b, a + b` |
| 2 | Prompts the user for the number of terms | Supported | `input("How many terms? ")` |
| 3 | Prints the series as a list | Supported | `print(fibonacci(n))` |
| 4 | Iterative implementation | Supported | Uses a `for` loop, no recursion |
| 5 | Validates input | Not Supported | `int(input(...))` raises `ValueError` on `abc` or `3.5`. Negative `n` silently returns `[]` |
| 6 | Supports very large terms | Supported | Python ints are unbounded (limited only by time and memory) |
| 7 | Can be imported with `from fibonacci import fibonacci` | Not Supported | No `if __name__ == "__main__":` guard, so importing runs `input()` and waits for the user |
| 8 | No external dependencies | Supported | No `import` statements |
| 9 | Requires Python 3 | Supported | Code runs on Python 3 |
| 10 | Example: `10` gives `[0, 1, 1, 2, 3, 5, 8, 13, 21, 34]` | Supported | Loop result |
| 11 | Example: `0` gives `[]` | Supported | `range(0)` is empty |
| 12 | Project structure includes `README.md` and `LICENSE` | Unverified | Cannot be confirmed from the code |
| 13 | MIT License | Unverified | Not stated in the code |

## Summary

- Not Supported: claims 5 and 7
- Unverified: claims 12 and 13
- All other claims are Supported
