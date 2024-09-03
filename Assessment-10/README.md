# Assessment 10: Exception Handling

## Objective

Learn how to handle runtime errors gracefully using try-catch blocks, and how to throw custom exceptions.

## Instructions

1. Create a file named `Assessment_10.cs`.
2. Write a C# program that:
   - Asks the user to enter two integers.
   - Tries to divide the first integer by the second, catching any `DivideByZeroException`.
   - Throws a custom exception if the user enters a negative number.

3. Compile and run the program.

## Expected Output

```c#
Enter two integers: 10 0 Cannot divide by zero!

Enter two integers: -10 2 Error: Negative numbers are not allowed.
```

## Skills Covered

- Implementing try-catch blocks for error handling.
- Catching specific exceptions.
- Throwing and catching custom exceptions.
- Understanding the importance of robust error handling.
