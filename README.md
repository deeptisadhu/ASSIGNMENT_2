# ASSIGNMENT_2
TASK3 :-
# Even or Odd Number Checker

## Description
This is a simple Python program that takes an integer input from the user, checks whether the number is even or odd using an `if-else` statement, and then displays the result accordingly.

## Features
- Takes an integer input from the user.
- Determines whether the number is even or odd.
- Displays the result to the user.

## Prerequisites
- Python 3.x must be installed on your system.

## How to Run the Program
1. Open a terminal or command prompt.
2. Navigate to the directory where the Python script is saved.
3. Run the script using the following command:


   ```sh
   python even_odd_checker.py
   ```
4. Enter an integer when prompted.
5. The program will display whether the number is even or odd.

## Example Usage
```
Enter a number: 7
7 is an odd number.
```
```
Enter a number: 10
10 is an even number.
```

## Code Overview
The program follows these steps:
1. Accepts an integer input from the user.
2. Uses the modulo operator `%` to check divisibility by 2.
3. If the remainder is 0, it prints that the number is even; otherwise, it prints that the number is odd.

## Sample Code
```python
# Even or Odd Number Checker

def check_even_odd():
    num = int(input("Enter a number: "))
    if num % 2 == 0:
        print(f"{num} is an even number.")
    else:
        print(f"{num} is an odd number.")

# Run the function
check_even_odd()
```

## License
This project is open-source and available for modification and distribution under the MIT License.

TASK4 :-

# Sum of Numbers from 1 to 50

## Description
This is a simple Python program that uses a `for` loop to iterate over numbers from 1 to 50, calculates the sum of all integers in this range, and then displays the sum.

## Features
- Iterates through numbers from 1 to 50.
- Computes the sum of these numbers.
- Displays the final sum to the user.

## Prerequisites
- Python 3.x must be installed on your system.

## How to Run the Program
1. Open a terminal or command prompt.
2. Navigate to the directory where the Python script is saved.
3. Run the script using the following command:
   ```sh
   python sum_numbers.py
   ```
4. The program will display the total sum of numbers from 1 to 50.

## Example Output
```
The sum of numbers from 1 to 50 is: 1275
```

## Code Overview
The program follows these steps:
1. Initializes a variable to store the sum.
2. Uses a `for` loop to iterate through numbers from 1 to 50.
3. Adds each number to the sum.
4. Displays the final sum.

## Sample Code
```python
# Sum of Numbers from 1 to 50

def calculate_sum():
    total = 0
    for num in range(1, 51):
        total += num
    print(f"The sum of numbers from 1 to 50 is: {total}")

# Run the function
calculate_sum()
```

## License
This project is open-source and available for modification and distribution under the MIT License.


