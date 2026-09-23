# Python Basic Programs

This repository contains simple Python programs for beginner practice.

## Programs Included

### 1. Binary Numbers Divisible by 5

This program accepts comma-separated binary numbers and prints the numbers that are divisible by 5.

```python
a = input().split(",")

for i in a:
    if int(i, 2) % 5 == 0:
        print(i, end=" ")
```

**Example Input**
```text
0100,0011,1010,1001
```

**Output**
```text
1010
```

**Screenshot**

![Binary Divisible by 5](binary_divisible_by_5.png)

---

### 2. Count Letters and Digits

This program counts the number of letters and digits in a sentence.

```python
text = input("Enter a sentence: ")

letters = 0
digits = 0

for ch in text:
    if ch.isalpha():
        letters += 1
    elif ch.isdigit():
        digits += 1

print("LETTERS", letters)
print("DIGITS", digits)
```

**Screenshot**

![Letters and Digits](letters_and_digits.png)

---

### 3. Factorial of a Number

This program calculates the factorial of a given number using a `for` loop.

```python
n = int(input())

fact = 1

for i in range(1, n + 1):
    fact = fact * i

print(fact)
```

**Example Input**
```text
5
```

**Output**
```text
120
```

**Screenshot**

![Factorial](factorial.png)

---

## Concepts Practiced

- `input()`
- `int()`
- `split()`
- `for` loop
- `range()`
- `if` / `elif`
- `isalpha()`
- `isdigit()`
- Binary to decimal conversion
- Modulus operator `%`
- Factorial calculation
- `print()`

## Repository Structure

```text
python-basic-programs/
│
├── README.md
├── binary_divisible_by_5.png
├── letters_and_digits.png
└── factorial.png
```

## Author

Python Beginner Practice
