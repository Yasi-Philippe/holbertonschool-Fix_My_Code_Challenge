# Challenge

Broken source code to read, debug, and fix. Each file below is a single task:
figure out what the program is meant to do, locate the bug, and correct it with
the smallest sensible change.

## Tasks

### `0-fizzbuzz.py`

A FizzBuzz implementation. Given a number `n`, it prints the numbers from
`1` to `n` separated by a space, with the following replacements:

- multiples of **3** → `Fizz`
- multiples of **5** → `Buzz`
- multiples of **both 3 and 5** → `FizzBuzz`

**Usage**

```bash
chmod +x 0-fizzbuzz.py
./0-fizzbuzz.py <number>
```

**Example**

```bash
$ ./0-fizzbuzz.py 16
1 2 Fizz 4 Buzz Fizz 7 8 Fizz Buzz 11 Fizz 13 14 FizzBuzz 16
```

Running it with no argument prints a usage message and exits with status `1`:

```bash
$ ./0-fizzbuzz.py
Missing number
Usage: ./0-fizzbuzz.py <number>
Example: ./0-fizzbuzz.py 89
```
