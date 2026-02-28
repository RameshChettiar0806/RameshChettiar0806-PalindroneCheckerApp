# Palindrome Checker App

A comprehensive Java application demonstrating multiple approaches to checking palindromes, progressing from basic implementations to optimized solutions.

## Overview

This project contains 8 different use cases (UCs) implementing various palindrome-checking techniques, each building upon the previous approach with improvements in logic, efficiency, and data structures.

## Project Structure

```
RameshChettiar0806-PalindromeCheckerApp/
├── App/
│   └── src/
│       ├── UC01PallindromeCheckerApp.java
│       ├── UC02PallindromeCheckerApp.java
│       ├── UC03PallindromeCheckerApp.java
│       ├── UC04PallindromeCheckerApp.java
│       ├── UC05PallindromeCheckerApp.java
│       ├── UC06PallindromeCheckerApp.java
│       ├── UC07PallindromeCheckerApp.java
│       └── UC08PallindromeCheckerApp.java
├── .idea/                    # IntelliJ IDEA configuration
├── out/                      # Compiled class files
├── LICENSE
└── README.md
```

## Use Cases

| UC | Title                    | Approach |
|:--:|:-------------------------|----------|
| **UC1** | **Welcome Page**         | **Basic introduction** |
| **UC2** | **Hardcoded Palindrome** | **Static input validation** |
| **UC3** | **String Reverse**       | **Simple string reversal method** |
| **UC4** | **Character Array**      | **Array-based palindrome checking** |
| **UC5** | **Stack-Based**          | **Stack data structure implementation** |
| **UC6** | **Queue & Stack**        | **Dual data structure approach** |
| **UC7** | **Deque Optimization**   | **Optimized deque implementation** |
| **UC8** | **Linked List**          | **Linked list-based approach** |

## Getting Started

### Prerequisites
- Java 8 or higher
- IntelliJ IDEA or any Java IDE (or command line)

### Running the Application

#### Using IDE
1. Open the project in IntelliJ IDEA
2. Navigate to `App/src/` directory
3. Right-click on any `UCSomethingPallindromeCheckerApp.java` file
4. Select **Run** to execute

#### Using Command Line
```bash
cd App/src
javac UC01PallindromeCheckerApp.java
java UC01PallindromeCheckerApp
```

## Key Concepts

- **Palindrome**: A string that reads the same forward and backward (case-insensitive, ignoring spaces)
- **Data Structures**: Explores Stack, Queue, Deque, and Linked List implementations
- **Algorithm Optimization**: Each UC demonstrates progressive refinement in time and space complexity

## Branch Structure

- **main** - Default branch containing the latest code
- **UC1-UC8** - Individual feature branches for each use case implementation

> **Note**: This project is evolving. More use cases (UC09 onwards) will be added in the future.

## Technologies Used

- **Language**: Java
- **IDE**: IntelliJ IDEA
- **Version Control**: Git & GitHub
- **Build Type**: Standard Java compilation

## Contributing

This is a learning project demonstrating palindrome-checking implementations. Contributions and improvements are welcome!

## License

This project is licensed under the LICENSE file included in the repository.

---

**Author**: Ramesh Chettiar  
**Last Updated**: January 2025
