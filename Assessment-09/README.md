# Assessment 09: Interfaces and Abstract Classes

## Objective

Learn how to use interfaces and abstract classes to define contracts for classes and provide a common base for related classes.

## Instructions

1. Create a file named `Assessment_09.cs`.
2. Write a C# program that:
   - Defines an interface `IShape` with methods `CalculateArea()` and `CalculatePerimeter()`.
   - Defines an abstract class `Shape` that implements `IShape` and adds an additional property `Name`.
   - Creates classes `Rectangle` and `Circle` that inherit from `Shape` and implement the `CalculateArea()` and `CalculatePerimeter()` methods.
   - Demonstrates the usage of these classes by creating instances and calling their methods.

3. Compile and run the program.

## Expected Output

```c#
Rectangle Area: 20 Rectangle Perimeter: 18 Circle Area: 28.27 Circle Perimeter: 18.85
```

## Skills Covered

- Defining and implementing interfaces.
- Working with abstract classes and abstract methods.
- Understanding the difference between interfaces and abstract classes.
- Implementing and using derived classes.
