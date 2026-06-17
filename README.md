# 📘 Introduction to C++ Programming Language

<div align="center">

![C++ Logo](https://upload.wikimedia.org/wikipedia/commons/1/18/ISO_C%2B%2B_Logo.svg)

## A Complete Beginner's Guide for Class 11 Students

### Author: Abhaya Bikram Shahi

Learn • Code • Create

</div>

---

# 📖 About This Book

This repository contains a complete introduction to the C++ Programming Language designed for Class 11 Computer Science students and beginners.

C++ is a powerful, fast, and widely used programming language used in:

- Operating Systems
- Game Development
- Artificial Intelligence
- Robotics
- Desktop Applications
- Embedded Systems
- Scientific Computing

---

# 👨‍💻 Author

## Abhaya Bikram Shahi

Student • Web Developer • App Developer • Programming Enthusiast

**Country:** Nepal

### About the Author

Abhaya Bikram Shahi is passionate about programming, software development, web technologies, mobile applications, and teaching technology to beginners.

---

# 📚 Table of Contents

1. Introduction
2. History of C++
3. Features of C++
4. Applications of C++
5. Structure of a Program
6. Hello World Program
7. Data Types
8. Variables
9. Operators
10. Conditional Statements
11. Loops
12. Arrays
13. Vectors
14. Strings
15. Functions
16. Pointers
17. Dynamic Memory Allocation
18. Complete Program Example

---

# 🚀 Introduction to C++

C++ is a general-purpose programming language developed by Bjarne Stroustrup in 1979.

It was designed as an extension of the C language and introduced Object-Oriented Programming concepts.

---

# 📜 History of C++

| Year | Event |
|--------|---------|
| 1979 | Created by Bjarne Stroustrup |
| 1983 | Renamed to C++ |
| 1998 | First ISO Standard |
| Today | Used worldwide |

---

# ⭐ Features of C++

- Fast Execution
- Object-Oriented
- Portable
- Rich Standard Library
- Dynamic Memory Management
- High Performance

---

# 🌍 Applications of C++

- Operating Systems
- Game Engines
- Browsers
- Database Systems
- AI Applications
- Embedded Systems
- Robotics

---

# 🏗 Program Structure

```cpp
#include <iostream>

int main()
{
    std::cout << "Hello World";
    return 0;
}
```

---

# 👋 Hello World Program

```cpp
#include <iostream>

int main()
{
    std::cout << "Hello, World!";
    return 0;
}
```

### Output

```text
Hello, World!
```

---

# 🔢 Data Types

| Data Type | Example |
|------------|---------|
| int | 10 |
| float | 3.14 |
| double | 10.567 |
| char | A |
| bool | true |
| string | Hello |

Example:

```cpp
int age = 16;
float height = 5.8;
char grade = 'A';
bool passed = true;
```

---

# ➕ Operators

```cpp
+
-
*
/
%
==
!=
>
<
>=
<=
```

Example:

```cpp
int a = 10;
int b = 5;

std::cout << a + b;
std::cout << a - b;
std::cout << a * b;
```

---

# 🔀 Conditional Statements

## if Statement

```cpp
if(age >= 18)
{
    std::cout << "Adult";
}
```

## if-else Statement

```cpp
if(age >= 18)
{
    std::cout << "Adult";
}
else
{
    std::cout << "Minor";
}
```

---

# 🔄 Loops

## For Loop

```cpp
for(int i = 0; i < 5; i++)
{
    std::cout << i;
}
```

## While Loop

```cpp
int i = 0;

while(i < 5)
{
    std::cout << i;
    i++;
}
```

---

# 📦 Arrays

```cpp
int marks[5] = {70, 80, 90, 85, 95};
```

---

# 📋 Vectors

```cpp
#include <vector>

std::vector<int> numbers = {10,20,30,40,50};
```

---

# 📝 Strings

```cpp
#include <string>

std::string name = "Abhaya";
```

Length:

```cpp
name.length();
```

---

# ⚙ Functions

```cpp
int add(int a, int b)
{
    return a + b;
}
```

Usage:

```cpp
int result = add(10,20);
```

---

# 🎯 Pointers

```cpp
int value = 42;
int* ptr = &value;

std::cout << *ptr;
```

---

# 💾 Dynamic Memory Allocation

```cpp
int* numbers = new int[5];
```

Free Memory:

```cpp
delete[] numbers;
```

---

# 🖥 Complete Program

```cpp
#include <iostream>
#include <vector>
#include <string>

int add(int a, int b)
{
    return a + b;
}

int main()
{
    std::cout << "Introduction to C++" << std::endl;

    int age = 16;
    float pi = 3.14f;

    std::cout << age << std::endl;
    std::cout << pi << std::endl;

    int result = add(10,20);

    std::cout << result << std::endl;

    return 0;
}
```

---

# 📚 What You Will Learn

✅ Variables

✅ Data Types

✅ Operators

✅ Conditions

✅ Loops

✅ Arrays

✅ Vectors

✅ Strings

✅ Functions

✅ Pointers

✅ Dynamic Memory

---

# 🎓 Conclusion

C++ is one of the most important programming languages in computer science. Learning C++ builds a strong foundation for software development, competitive programming, game development, and advanced computer science topics.

---

## © 2026 Abhaya Bikram Shahi

All Rights Reserved.    std::cout << "Character: " << grade << std::endl;
    std::cout << "Constant MAX: " << MAX << "\n\n";
    
    // Arithmetic operations
    int x = 10, y = 20;
    std::cout << "x = " << x << ", y = " << y << std::endl;
    std::cout << "Sum: " << (x + y) << std::endl;
    std::cout << "Product: " << (x * y) << std::endl;
    std::cout << "Division: " << (y / x) << "\n\n";
    
    // Control structures - if-else
    if (age >= 18) {
        std::cout << "You are an adult.\n";
    } else {
        std::cout << "You are a minor.\n";
    }
    
    // Ternary operator
    std::cout << "Status: " << (age >= 18 ? "Adult" : "Minor") << "\n\n";
    
    // Loops
    std::cout << "For loop (0 to 4):\n";
    for(int i = 0; i < 5; i++) {
        std::cout << i << " ";
    }
    std::cout << "\n\n";
    
    // While loop
    std::cout << "While loop:\n";
    int i = 0;
    while(i < 5) {
        std::cout << i << " ";
        i++;
    }
    std::cout << "\n\n";
    
    // Vectors (modern C++ arrays)
    std::vector<int> numbers = {10, 20, 30, 40, 50};
    std::cout << "Vector elements:\n";
    printArray(numbers);
    std::cout << "\n";
    
    // Strings
    std::string name = "C++ Language";
    std::cout << "String: " << name << std::endl;
    std::cout << "String length: " << name.length() << "\n\n";
    
    // Function call
    int result = add(15, 27);
    std::cout << "Function result (15 + 27): " << result << "\n\n";
    
    // Pointers demonstration
    int value = 42;
    int *ptr = &value;
    std::cout << "Value: " << value << std::endl;
    std::cout << "Pointer address: " << ptr << std::endl;
    std::cout << "Value via pointer: " << *ptr << "\n\n";
    
    // Dynamic memory allocation (new/delete)
    int* dynamic = new int[3];
    dynamic[0] = 100;
    dynamic[1] = 200;
    dynamic[2] = 300;
    std::cout << "Dynamic array: ";
    for(int j = 0; j < 3; j++) {
        std::cout << dynamic[j] << " ";
    }
    std::cout << std::endl;
    delete[] dynamic;
    
    std::cout << "\nThis program demonstrates core C++ concepts:\n";
    std::cout << "- Data types, variables, constants\n";
    std::cout << "- Input/Output with std::cout\n";
    std::cout << "- Operators and expressions\n";
    std::cout << "- Control structures (if, loops)\n";
    std::cout << "- Vectors and strings\n";
    std::cout << "- Functions\n";
    std::cout << "- Pointers\n";
    std::cout << "- Dynamic memory (new/delete)\n";
    
    return 0;
}

// Function definitions
int add(int a, int b) {
    return a + b;
}

void printArray(const std::vector<int>& arr) {
    for(int num : arr) {
        std::cout << num << " ";
    }
    std::cout << std::endl;
}
