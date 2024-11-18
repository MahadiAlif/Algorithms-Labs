# Lab 1: Input Verification and Morse Code Translator

This directory contains solutions to the **Lab 1 exercises** from the Algorithms & Programming course at Politecnico di Torino. The exercises focus on fundamental programming concepts like arrays, strings, functions, file management, and command-line parameters.

---

## 📚 Learning Objectives

- Arrays and multidimensional arrays
- String manipulation
- Input verification and conversion
- File management
- Command-line parameters

---

## 🛠️ Lab Exercises

### **1. Input Verification and Conversion**
#### **a) Integer Conversion with `atoi`**
Write a program that:
- Accepts a string input from the user (representing the quantity of tokens).
- Converts the string to an integer using `atoi`.

**Example Output**:
- Please choose the quantity of tokens to deposit: 1234 The tokens value you entered is: 1234
- Please choose the quantity of tokens to deposit: abc The tokens value you entered is: 0


#### **b) Floating-Point Conversion with `atof`**
Modify the previous program to handle deposit amounts in a virtual ATM. Convert the input string to a float with two decimal digits using `atof`.

**Example Output**:
- Enter the amount you wish to deposit: 1234.1234 You deposited: 1234.12


#### **c) Passport Character Length Verification**
Create a program to verify that an Italian passport number has exactly 9 characters using `strlen`.

**Example Output**:
- Please enter the passport number: AB1234567 The passport you entered is: AB1234567

  
#### **d) Passport Format Verification**
Enhance the previous program to ensure the passport format is valid: the first two characters are alphabets, followed by seven digits. Use `isalpha` and `isdigit`.

**Example Output**:
- Please enter the passport number: AB1234567 The passport you entered is: AB1234567
- Please enter the passport number: ABC123456 The passport you entered is invalid.

  
#### **e) Case Conversion**
Write a program that accepts user input in both uppercase and lowercase for a Yes/No prompt. Use `toupper` or `tolower` for input normalization.

**Example Output**:
- Digit (Y) to continue and (N) to quit: y Continuing the application...

  
---

### **2. Morse Code Translator**
Develop a program to encode and decode messages using the International Morse Code.

#### **Requirements**:
- Use an efficient data structure (e.g., a zero-based array) to map characters to their Morse code representations.
- Implement an interactive menu with options to:
  - Encode a message.
  - Decode a message.
  - Exit the program.

#### **Implementation Details**:
- Read text from an input file and write the output to another file.
- Represent Morse symbols within words as spaces and separate words using `/`.

**Example Output**:
- (E)ncode (D)ecode (X)it >>> e Input file name > plaintext.in Output file name > encoded.out Encoded message saved to file encoded.out Encoded message: .... . .-.. .-.. --- / .-- --- .-. .-.. -..
  
