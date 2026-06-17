# Introduction to C++ Programming Language - Full Code Example

## Complete C++ Program

```cpp
#include <iostream>
#include <string>
#include <vector>

// Function prototypes
int add(int a, int b);
void printArray(const std::vector<int>& arr);

int main() {
    // Variables and data types
    int age = 25;
    float pi = 3.14159f;
    double bigNumber = 12345.6789;
    char grade = 'A';
    const int MAX = 100;
    
    std::cout << "=== Introduction to C++ Language ===\n\n";
    std::cout << "Hello, World! This is a complete C++ program.\n\n";
    
    // Basic output
    std::cout << "Integer: " << age << std::endl;
    std::cout << "Float: " << pi << std::endl;
    std::cout << "Double: " << bigNumber << std::endl;
    std::cout << "Character: " << grade << std::endl;
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
