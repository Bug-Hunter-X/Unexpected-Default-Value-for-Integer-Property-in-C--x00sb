# Unexpected Default Value for Integer Property in C#

This repository demonstrates a potential issue with integer properties in C#.  If an integer property is not explicitly initialized in the constructor, it might not always have the default value of 0, leading to unpredictable results, particularly in multithreaded scenarios.

The `bug.cs` file shows a class with an integer property that's not explicitly initialized. The `bugSolution.cs` file demonstrates the correct approach to initialize the property in the constructor.