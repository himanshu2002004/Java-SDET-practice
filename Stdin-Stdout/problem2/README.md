# Java Stdin and Stdout II

## Problem Statement

In this challenge, you must read an **integer**, a **double**, and a **String** from standard input (`stdin`), then print them in the required format.

## Input Format

There are three lines of input:

1. The first line contains an integer.
2. The second line contains a double.
3. The third line contains a String.

## Output Format

Print the following:

- `String:` followed by the input string.
- `Double:` followed by the input double.
- `Int:` followed by the input integer.

## Sample Input

```text
42
3.1415
Welcome to Java
```

## Sample Output

```text
String: Welcome to Java
Double: 3.1415
Int: 42
```

## Java Concepts Used

- `Scanner` class
- `nextInt()`
- `nextDouble()`
- `nextLine()`
- Input buffer handling
- String input and output

## Learning Outcome

This challenge demonstrates how to:
- Read different data types from user input.
- Handle the newline character left in the input buffer after reading numeric values.
- Read an entire line of text using `nextLine()`.
- Print output in the required format.
