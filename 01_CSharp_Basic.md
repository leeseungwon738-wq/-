# C# Beginner Concepts

## Variables
Variables are used to store data values. In C#, a variable must be declared before it can be used.

### Declaration and Initialization
To declare a variable in C#, you use the following syntax:
```csharp
int x; // Declaration
x = 5; // Initialization
```
You can also declare and initialize a variable in one line:
```csharp
int y = 10;
```

## Data Types
C# is a strongly typed language, which means that every variable must have a data type. Here are some common data types:

- **int**: Represents integer values (whole numbers).
    ```csharp
    int age = 30;
    ```
- **double**: Represents floating-point numbers (numbers with decimals).
    ```csharp
    double price = 19.99;
    ```
- **char**: Represents a single character.
    ```csharp
    char initial = 'A';
    ```
- **string**: Represents a sequence of characters (text).
    ```csharp
    string name = "John";
    ```
- **bool**: Represents a boolean value (true or false).
    ```csharp
    bool isAvailable = true;
    ```

## Basic Syntax
C# syntax is similar to other C-based languages. Here are some key features:

### Semicolons
Each statement in C# must end with a semicolon (`;`). For example:
```csharp
Console.WriteLine("Hello, World!");
```

### Comments
You can add comments in your code using `//` for single-line comments and `/* ... */` for multi-line comments:
```csharp
// This is a single-line comment
/* This is a multi-line comment */
```

### Control Structures
Control structures such as `if`, `else`, `for`, and `while` are used to control the flow of execution.

#### Example of a simple `if` statement:
```csharp
if (age < 18)
{
    Console.WriteLine("You are a minor.");
}
else
{
    Console.WriteLine("You are an adult.");
}
```

#### Example of a `for` loop:
```csharp
for (int i = 0; i < 5; i++)
{
    Console.WriteLine(i);
}
```

### Method Definition
In C#, methods are defined using the following syntax:
```csharp
public void MyMethod()
{
    Console.WriteLine("This is a method.");
}
```

## Conclusion
Understanding these basic concepts of C# will help you build a solid foundation as you start programming. Try experimenting with the code examples to see how they work!