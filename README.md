# Python Basic Programs

This repository contains simple Python programs for beginners to
practice **input, loops, range, string splitting, and binary number
conversion**.

## 1. Print Numbers in a Range

### Program

``` python
n = int(input())
n2 = int(input())

for i in range(n, n2):
    print(i)
```

### Example Input

``` text
1
5
```

### Output

``` text
1
2
3
4
```

### Explanation

-   `input()` gets the value from the user.
-   `int()` converts the input into an integer.
-   `range(n, n2)` generates numbers from `n` up to `n2 - 1`.
-   `for` loop prints each number.

------------------------------------------------------------------------

## 2. Check Binary Numbers Divisible by 5

### Program

``` python
a = input().split(",")

for i in a:
    if int(i, 2) % 5 == 0:
        print(i, end=" ")
```

### Example Input

``` text
0100,0011,1010,1001
```

### Output

``` text
1010
```

### Explanation

-   `split(",")` separates the input using commas.
-   `for i in a` checks each binary number.
-   `int(i, 2)` converts the binary number into decimal.
-   `% 5 == 0` checks whether the number is divisible by 5.
-   `print(i, end=" ")` prints the matching binary number.

## Concepts Practiced

-   `input()`
-   `int()`
-   `split()`
-   `for` loop
-   `range()`
-   Binary to decimal conversion
-   Modulus operator `%`
-   `print()`

## Author

Beginner Python Practice
