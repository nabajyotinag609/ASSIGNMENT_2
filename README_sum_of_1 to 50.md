# Sum of Integers from 1 to 50 Using a Loop

## Description

This Python program calculates the **sum of all integers from 1 to 50** using a `for` loop. It demonstrates basic looping and accumulation logic in Python.

## How It Works

* A variable `s` is initialized to `0` to store the sum.
* A `for` loop iterates through numbers from `1` to `50`.
* Each number is added to `s`.
* After the loop completes, the final sum is printed.

## Logic Used

The program adds numbers sequentially:
[
\text{Sum} = 1 + 2 + 3 + \dots + 50
]

## Program Code

```python
s = 0
for num in range(1,51):
    s = s + num
print("The sum of numbers from 1 to 50 is:", s)
```

## How to Run

1. Ensure Python 3.x is installed.
2. Save the file as `sum_1_to_50.py`.
3. Open a terminal or command prompt.
4. Run the program using:

   ```
   python sum_1_to_50.py
   ```

## Output

```
The sum of numbers from 1 to 50 is: 1275
```

## Note

The same result can also be calculated using the mathematical formula:
[
\text{Sum} = \frac{n(n+1)}{2}
]
where ( n = 50 ).

---
