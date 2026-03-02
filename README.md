# Palindrome Checker App

A comprehensive Java application demonstrating multiple approaches to checking palindromes, progressing from basic implementations to optimized, object-oriented, and performance-comparison solutions.

## Overview

This project demonstrates **13 different use cases (UC01–UC13)** implementing various palindrome-checking techniques.

Each use case builds on the previous one, introducing:

- Better logic refinement
- Data structure usage
- Recursion
- Normalization
- Object-Oriented Programming
- Strategy Design Pattern
- Performance benchmarking using `System.nanoTime()`

This project showcases both algorithmic understanding and software design evolution.

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
│       ├── UC08PallindromeCheckerApp.java
│       ├── UC09PallindromeCheckerApp.java
│       ├── UC10PallindromeCheckerApp.java
│       ├── UC11PallindromeCheckerApp.java
│       ├── UC12PallindromeCheckerApp.java
│       └── UC13PallindromeCheckerApp.java
├── .idea/                    # IntelliJ IDEA configuration
├── out/                      # Compiled class files
├── LICENSE
└── README.md
```

## Use Cases Overview

| UC | Title | Approach | Key Concept |
|:--:|:------|:---------|:------------|
| **UC01** | Welcome Page | Basic structure | Program entry point |
| **UC02** | Hardcoded Palindrome | Static comparison | Simple logic |
| **UC03** | String Reverse | Reverse & compare | String manipulation |
| **UC04** | Character Array | Two-pointer method | Array processing |
| **UC05** | Stack-Based | Stack | LIFO principle |
| **UC06** | Queue + Stack | Dual structure | FIFO + LIFO comparison |
| **UC07** | Deque Optimization | Deque | Efficient front/back removal |
| **UC08** | Linked List | LinkedList | Dynamic structure |
| **UC09** | Recursive Approach | Recursion | Divide & conquer |
| **UC10** | Normalized Palindrome | Regex + cleaning | Real-world validation |
| **UC11** | OOP Service Design | PalindromeService | Encapsulation |
| **UC12** | Strategy Pattern | PalindromeStrategy | Runtime polymorphism |
| **UC13** | Algorithm Benchmarking | nanoTime() comparison | Performance analysis |

## Detailed Evolution

### UC01 – UC02 (Basics)
- Basic program setup
- Hardcoded string validation
- Simple conditional logic

### UC03 – UC04 (String + Array Efficiency)
- String reversal method
- Two-pointer array traversal
- Improved efficiency over reverse-string approach

**Typical Complexity**
- Time Complexity: **O(n)**
- Space Complexity: **O(n)** (if reversed string stored)

### UC05 – UC08 (Data Structure Phase)

**Stack-Based**
- Push all characters
- Pop and compare

**Queue + Stack**
- Compare FIFO and LIFO behavior

**Deque**
- Remove from front and rear simultaneously
- Efficient front/back access

**LinkedList**
- Dynamic insertion & removal

**Typical Complexity**
- Time Complexity: **O(n)**
- Space Complexity: **O(n)**

### UC09 (Recursive Approach)
Uses recursive calls:
- `isPalindrome(str, left, right)`
- Base case: `left >= right`
- Recursive shrink inward

**Complexity**
- Time Complexity: **O(n)**
- Space Complexity: **O(n)** (recursion stack)

### UC10 (Real-World Normalization)
- Converts to lowercase
- Removes spaces
- Removes special characters

Example:
- "A man, a plan, a canal: Panama"

Normalized using:
- `toLowerCase()`
- `replaceAll("[^a-z0-9]", "")`

Now properly validates as a palindrome.

### UC11 (Object-Oriented Design)
Introduces:
- `PalindromeService` class

Encapsulates palindrome logic, promotes separation of concerns, and improves maintainability.

### UC12 (Strategy Design Pattern)
Introduces:
- `PalindromeStrategy` interface
- Multiple implementations (examples):
  - `StackStrategy`
  - `DequeStrategy`
  - `RecursiveStrategy`
  - `ArrayStrategy`

Allows runtime switching, e.g.:
```java
service.setStrategy(new StackStrategy());
```

**Design Benefits**
- Open/Closed Principle
- Easy extension
- Cleaner architecture

### UC13 (Algorithm Benchmarking & Complexity Analysis)
Runs multiple palindrome algorithms and measures execution time using:
- `System.nanoTime()`

Compares performance across approaches and prints:
- Palindrome result
- Execution time per approach

## Complexity Summary (UC01 – UC13)

| Approach | Time Complexity | Space Complexity |
|---------|------------------|------------------|
| Reverse String | O(n) | O(n) |
| Two-Pointer | O(n) | O(1) |
| Stack | O(n) | O(n) |
| Queue + Stack | O(n) | O(n) |
| Deque | O(n) | O(n) |
| LinkedList | O(n) | O(n) |
| Recursion | O(n) | O(n) |
| Normalized | O(n) | O(n) |
| Strategy Pattern | O(n) | Depends on implementation |
| Benchmarking | O(n) per algorithm | O(1) extra |

## Getting Started

### Prerequisites
- Java 8 or higher
- IntelliJ IDEA or any Java IDE (or command line)

### Running the Application

#### Using IDE
1. Open the project in IntelliJ IDEA
2. Navigate to `App/src/`
3. Right-click on any `UCxxPallindromeCheckerApp.java` file
4. Select **Run**

#### Using Command Line
```bash
cd App/src
javac UC13PallindromeCheckerApp.java
java UC13PallindromeCheckerApp
```

## Learning Outcomes

After completing UC01–UC13, you understand:
- Basic Java program structure
- String manipulation
- Data structures (Stack, Queue, Deque, LinkedList)
- Recursion
- Regular expressions
- Object-Oriented Programming
- Strategy Design Pattern
- Performance measurement
- Time & space complexity analysis

## Future Enhancements

Possible UC14+ ideas:
- Multithreading comparison
- Large dataset benchmarking
- File input support
- GUI version (JavaFX/Swing)
- REST API version (Spring Boot)

## Technologies Used
- **Language**: Java (8+)
- **IDE**: IntelliJ IDEA
- **Version Control**: Git & GitHub
- **Build Type**: Standard Java compilation

## License
This project is licensed under the LICENSE file included in the repository.

---

**Author**: Ramesh Chettiar  
**Last Updated**: 2026-03-02 11:05:17
