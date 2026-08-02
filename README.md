# 🔁 PalindromeCheckerApp

A **console-based Java application** that checks whether a given input (string or number) is a **palindrome**. A palindrome is a value that reads the same forward and backward.

---

## 📌 Overview

The application allows users to:
- 🔤 Check if a string is a palindrome  
- 🔢 Check if a number is a palindrome  
- 🔍 Validate input before processing  
- ⚠️ Handle invalid inputs using exception handling  

This project is designed to strengthen **logic building, string manipulation, and basic algorithm design**.

---

## 📂 Progressive Use Cases

The codebase is organized as a step-by-step learning journey, starting from a basic CLI flow and evolving into object-oriented service structures, design patterns, and benchmarking.

Here is a summary of all **13 Use Cases** implemented in the repository:

| Step / Use Case | Source File & Class Symbol | Approach / Feature |
|:---|:---|:---|
| **UC 1** | [`UseCase1PalindromeCheckerApp.java`](file:///c:/Users/hp/OneDrive/Desktop/coding/step/PalindromeCheckerApp/src/UseCase1PalindromeCheckerApp.java)<br>👉 [`PalindromeChecker`](file:///c:/Users/hp/OneDrive/Desktop/coding/step/PalindromeCheckerApp/src/UseCase1PalindromeCheckerApp.java#L25) | Entry Point & Welcome Message |
| **UC 2** | [`UseCase2PalindromeCheckerApp.java`](file:///c:/Users/hp/OneDrive/Desktop/coding/step/PalindromeCheckerApp/src/UseCase2PalindromeCheckerApp.java)<br>👉 [`UseCase2PalindromeCheckerApp`](file:///c:/Users/hp/OneDrive/Desktop/coding/step/PalindromeCheckerApp/src/UseCase2PalindromeCheckerApp.java#L25) | Hardcoded iterative comparison |
| **UC 3** | [`UseCase3PalindromeCheckerApp.java`](file:///c:/Users/hp/OneDrive/Desktop/coding/step/PalindromeCheckerApp/src/UseCase3PalindromeCheckerApp.java)<br>👉 [`UseCase3PalindromeCheckerApp`](file:///c:/Users/hp/OneDrive/Desktop/coding/step/PalindromeCheckerApp/src/UseCase3PalindromeCheckerApp.java#L25) | String reversal construction |
| **UC 4** | [`UseCase4PalindromeCheckerApp.java`](file:///c:/Users/hp/OneDrive/Desktop/coding/step/PalindromeCheckerApp/src/UseCase4PalindromeCheckerApp.java)<br>👉 [`UseCase4PalindromeCheckerApp`](file:///c:/Users/hp/OneDrive/Desktop/coding/step/PalindromeCheckerApp/src/UseCase4PalindromeCheckerApp.java#L17) | Character array (`char[]`) & two-pointer technique |
| **UC 5** | [`UseCase5PalindromeCheckerApp.java`](file:///c:/Users/hp/OneDrive/Desktop/coding/step/PalindromeCheckerApp/src/UseCase5PalindromeCheckerApp.java)<br>👉 [`UseCase5PalindromeCheckerApp`](file:///c:/Users/hp/OneDrive/Desktop/coding/step/PalindromeCheckerApp/src/UseCase5PalindromeCheckerApp.java#L18) | LIFO comparison via `java.util.Stack` |
| **UC 6** | [`UseCase6PalindromeCheckerApp.java`](file:///c:/Users/hp/OneDrive/Desktop/coding/step/PalindromeCheckerApp/src/UseCase6PalindromeCheckerApp.java)<br>👉 [`UseCase6PalindromeCheckerApp`](file:///c:/Users/hp/OneDrive/Desktop/coding/step/PalindromeCheckerApp/src/UseCase6PalindromeCheckerApp.java#L27) | `Queue` (FIFO) and `Stack` (LIFO) comparison |
| **UC 7** | [`UseCase7PalindromeCheckerApp.java`](file:///c:/Users/hp/OneDrive/Desktop/coding/step/PalindromeCheckerApp/src/UseCase7PalindromeCheckerApp.java)<br>👉 [`UseCase7PalindromeCheckerApp`](file:///c:/Users/hp/OneDrive/Desktop/coding/step/PalindromeCheckerApp/src/UseCase7PalindromeCheckerApp.java#L25) | Double-ended queue matching using `java.util.Deque` |
| **UC 8** | [`UseCase8PalindromeCheckerApp.java`](file:///c:/Users/hp/OneDrive/Desktop/coding/step/PalindromeCheckerApp/src/UseCase8PalindromeCheckerApp.java)<br>👉 [`UseCase8PalindromeCheckerApp`](file:///c:/Users/hp/OneDrive/Desktop/coding/step/PalindromeCheckerApp/src/UseCase8PalindromeCheckerApp.java#L27) | Double-ended matching on `java.util.LinkedList` |
| **UC 9** | [`UseCase9RecursivePalindrome.java`](file:///c:/Users/hp/OneDrive/Desktop/coding/step/PalindromeCheckerApp/src/UseCase9RecursivePalindrome.java)<br>👉 [`UseCase9PalindromeCheckerApp`](file:///c:/Users/hp/OneDrive/Desktop/coding/step/PalindromeCheckerApp/src/UseCase9RecursivePalindrome.java#L27) | Recursive divide-and-conquer strategy |
| **UC 10** | [`UseCase10PalindromeCheckerApp.java`](file:///c:/Users/hp/OneDrive/Desktop/coding/step/PalindromeCheckerApp/src/UseCase10PalindromeCheckerApp.java)<br>👉 [`UseCase10PalindromeCheckerApp`](file:///c:/Users/hp/OneDrive/Desktop/coding/step/PalindromeCheckerApp/src/UseCase10PalindromeCheckerApp.java#L28) | Preprocessing and input normalization |
| **UC 11** | [`UseCase11PalindromeCheckerApp.java`](file:///c:/Users/hp/OneDrive/Desktop/coding/step/PalindromeCheckerApp/src/UseCase11PalindromeCheckerApp.java)<br>👉 [`UseCase11PalindromeCheckerApp`](file:///c:/Users/hp/OneDrive/Desktop/coding/step/PalindromeCheckerApp/src/UseCase11PalindromeCheckerApp.java#L24)<br>👉 [`PalindromeService`](file:///c:/Users/hp/OneDrive/Desktop/coding/step/PalindromeCheckerApp/src/UseCase11PalindromeCheckerApp.java#L51) | OOP encapsulation of validation logic |
| **UC 12** | [`UseCase12PalindromeCheckerApp.java`](file:///c:/Users/hp/OneDrive/Desktop/coding/step/PalindromeCheckerApp/src/UseCase12PalindromeCheckerApp.java)<br>👉 [`UseCase12PalindromeCheckerApp`](file:///c:/Users/hp/OneDrive/Desktop/coding/step/PalindromeCheckerApp/src/UseCase12PalindromeCheckerApp.java#L23)<br>👉 [`PalindromeStrategy`](file:///c:/Users/hp/OneDrive/Desktop/coding/step/PalindromeCheckerApp/src/UseCase12PalindromeCheckerApp.java#L50)<br>👉 [`StackStrategy`](file:///c:/Users/hp/OneDrive/Desktop/coding/step/PalindromeCheckerApp/src/UseCase12PalindromeCheckerApp.java#L63) | Strategy Design Pattern for dynamic algorithms |
| **UC 13** | [`UseCase13PalindromeCheckerApp.java`](file:///c:/Users/hp/OneDrive/Desktop/coding/step/PalindromeCheckerApp/src/UseCase13PalindromeCheckerApp.java)<br>👉 [`UseCase13PalindromeCheckerApp`](file:///c:/Users/hp/OneDrive/Desktop/coding/step/PalindromeCheckerApp/src/UseCase13PalindromeCheckerApp.java#L22) | Execution profiling & nanosecond benchmarking |

---

## 🎯 Objectives

- Understand palindrome logic  
- Practice string and number manipulation  
- Implement condition-based checking  
- Handle edge cases and invalid input  
- Build clean and modular Java code  

---

## 🧩 Core Functionalities

### 🔹 String Palindrome Check
- Accepts a string input  
- Reverses the string  
- Compares original and reversed values  

---

### 🔹 Number Palindrome Check
- Accepts numeric input  
- Reverses digits mathematically  
- Compares original number with reversed number  

---

### 🔹 Input Validation
- Ensures valid input is provided  
- Handles empty or null values  

---

### 🔹 Exception Handling
- Uses try-catch blocks  
- Prevents application crashes  
- Displays meaningful error messages  

---

## ⚙️ Features

- ✅ Supports both strings and numbers  
- ✅ Case-insensitive comparison (for strings)  
- ✅ Handles edge cases (empty, single character)  
- ✅ Exception handling for invalid input  
- ✅ Simple and user-friendly console output  

---

## 🧠 Concepts Covered

- String Manipulation  
- Loops and Conditionals  
- Functions/Methods  
- Exception Handling  
- Input Validation  
- Basic Algorithm Design  

---

## 📈 Learning Outcomes
- Build strong logical thinking skills
- Understand string and number operations
- Handle user input safely
- Learn basic algorithm implementation
- Improve debugging and testing skills

---
