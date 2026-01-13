# Check if a Number is Even or Odd

## Description

This Python program checks whether a given integer is **even** or **odd**. It takes an integer input from the user and determines its parity using the modulus (`%`) operator.

## How It Works

* The user is prompted to enter an integer.
* The program checks the remainder when the number is divided by `2`.
* If the remainder is `0`, the number is **Even**.
* Otherwise, the number is **Odd**.

## Logic Used

A number is:

* **Even** if `number % 2 == 0`
* **Odd** if `number % 2 != 0`

## Program Code

```python
num = int(input("Enter a Integer:"))

if num % 2 == 0:
    print(f"{num} is an EVEN Number.")
else:
    print(f"{num} is an ODD Number.")
```

## How to Run

1. Make sure Python is installed on your system.
2. Save the program in a file, for example: `even_odd.py`
3. Open a terminal or command prompt.
4. Run the program using:

   ```
   python even_odd.py
   ```
5. Enter an integer when prompted.

## Sample Input

```
Enter a Integer: 7
```

## Sample Output

```
7 is an ODD Number.
