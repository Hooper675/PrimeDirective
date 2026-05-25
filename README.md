# PrimeDirective

`PrimeDirective.java` is a simple Java utility class for prime number detection and filtering.

## Overview

- `isPrime(int number)` checks whether a single integer is a prime number.
- `onlyPrimes(int[] numbers)` filters an array and returns only the prime values.
- A `main` method demonstrates example usage and prints results.

## Requirements

- Java Development Kit (JDK) 8 or newer.

## Compile

From the directory containing `PrimeDirective.java`:

```bash
javac PrimeDirective.java
```

## Run

```bash
java PrimeDirective
```

## Example Output

This example prints the result of several prime checks and the prime values from an array:

```text
true
false
true
false
[29, 11, 101, 43, 89]
```

## File

- `PrimeDirective.java` — Java source file containing the prime utility class and example execution.

## Notes

- The prime check currently tests divisibility from `2` to `number - 1`.
- For larger inputs, it can be optimized using a square-root bound or more advanced prime-testing techniques.
