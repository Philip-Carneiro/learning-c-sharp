# Assessment 12: Delegates and Events

## Objective

Understand how to use delegates and events to implement event-driven programming in C#.

## Instructions

1. Create a file named `Assessment_12.cs`.
2. Write a C# program that:
   - Defines a delegate `Notify` and an event `OnProcessCompleted` using this delegate.
   - Defines a class `Process` that triggers the `OnProcessCompleted` event when a method `StartProcess` is called.
   - Demonstrates the use of the event by subscribing to it and handling the event in a separate method.

3. Compile and run the program.

## Expected Output

```c#
Process started... Process completed! Event fired!
```

## Skills Covered

- Understanding and using delegates.
- Declaring and triggering events.
- Subscribing to and handling events.
- Event-driven programming concepts.
