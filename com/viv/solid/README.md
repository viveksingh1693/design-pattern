# SOLID Design Principles

This repository contains code examples and explanations of the SOLID design principles in object-oriented programming (OOP). These principles aim to make software designs more understandable, flexible, and maintainable.

## SOLID Overview

The SOLID principles are:

1. **Single Responsibility Principle (SRP)**
   - A class should have only one reason to change, meaning it should have only one responsibility or job.
   - **Example**: A class responsible for handling user authentication should not handle logging file data.

2. **Open/Closed Principle (OCP)**
   - Software entities (classes, modules, functions) should be open for extension but closed for modification.
   - **Example**: You should be able to extend the behavior of a class by creating new classes, not by modifying existing ones.

3. **Liskov Substitution Principle (LSP)**
   - Objects of a superclass should be replaceable with objects of a subclass without altering the correctness of the program.
   - **Example**: If `Bird` is a superclass and `Penguin` is a subclass, then substituting `Bird` objects with `Penguin` should not introduce errors, even though penguins cannot fly.

4. **Interface Segregation Principle (ISP)**
   - Clients should not be forced to depend on interfaces they do not use.
   - **Example**: Instead of having a large interface with many unrelated methods, split it into smaller, more specific ones that clients need.

5. **Dependency Inversion Principle (DIP)**
   - High-level modules should not depend on low-level modules. Both should depend on abstractions.
   - **Example**: A `Car` class should depend on an `Engine` interface rather than a specific `Engine` implementation, allowing for more flexible engine swaps.

## Contents

- **Single Responsibility Principle (SRP)**: Explanation and code example.
- **Open/Closed Principle (OCP)**: Explanation and code example.
- **Liskov Substitution Principle (LSP)**: Explanation and code example.
- **Interface Segregation Principle (ISP)**: Explanation and code example.
- **Dependency Inversion Principle (DIP)**: Explanation and code example.

## Why Use SOLID Principles?

By adhering to SOLID principles:
- You make your code easier to understand and modify.
- Your software becomes more modular and flexible.
- You reduce the likelihood of bugs when extending functionality.

## Getting Started

Each principle is implemented in the `/src` folder, with clear documentation for each example.

## Contributing

Feel free to contribute by submitting issues or pull requests with new examples or improvements.

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
