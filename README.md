# Substring-in-Cpp
This repository contains a simple C++ program demonstrating the use of the substr() function to extract a substring from a given string.  The program takes a string and prints a portion of it starting from a specified index for a given length. 
# Substring in C++

This repository contains a simple C++ program that demonstrates how to extract a **substring from a string using the `substr()` function**.

## 📌 Program Description
The program uses the `substr(start, length)` method of the C++ `string` class to extract a part of a string starting from a given index for a specified number of characters.

In this example, a substring is extracted from the word **"programing"** and printed to the output.

## 🧠 Concepts Covered
- C++ string manipulation
- `substr()` function
- Index-based string access
- Basic input/output

## 💻 Source Code
```cpp
#include<iostream>
using namespace std;

int main(){
    string s = "programing";
    cout << s.substr(3,4);
    return 0;
}
