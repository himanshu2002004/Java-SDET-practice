# Java Output Formatting

## Problem Statement

In this challenge, you will use Java's `System.out.printf()` method to print formatted output.

For each line of input:

- Read a **String** and an **integer**.
- Print the **String** left-justified in a field of exactly **15 characters**.
- Print the **integer** using exactly **3 digits**. If the integer has fewer than three digits, pad it with leading zeros.

## Input Format

- There are **3 lines** of input.
- Each line contains:
  - A `String` (maximum of 10 alphabetic characters)
  - An `Integer` (between 0 and 999)

## Output Format

Print the following:

- A line containing `================================`
- Three formatted lines where:
  - The **String** is left-justified using **15 characters**
  - The **Integer** is displayed using **3 digits**, padded with leading zeros if necessary
- A closing line containing `================================`

## Sample Input

```text
java 100
cpp 65
python 50
```

## Sample Output

```text
================================
java           100
cpp            065
python         050
================================
```

## Java Concepts Used

- `Scanner` class
- `for` loop
- `System.out.printf()`
- Format specifiers
  - `%-15s` – Left-justify a string within 15 characters
  - `%03d` – Print an integer with leading zeros to make it 3 digits
  - `%n` – Print a new line

## Key Learning

This challenge demonstrates how to format console output using `printf()` in Java.

Example:

```java
System.out.printf("%-15s%03d%n", str, num);
```

Where:

- `%-15s` → Left-aligns the string in a field of 15 characters.
- `%03d` → Prints the integer using exactly 3 digits, adding leading zeros if needed.
- `%n` → Moves to the next line.
