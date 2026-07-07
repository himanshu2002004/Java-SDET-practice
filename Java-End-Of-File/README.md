# Java End-of-File (EOF)

## Problem Statement

Write a Java program that reads an unknown number of input lines until **End of File (EOF)** is reached.

For each line read from the input, print the **line number** (starting from `1`), followed by a single space, and then the content of that line.

The program should continue reading input until no more input is available.

---

## Input Format

- Read an unknown number of lines from standard input (`System.in`).
- Each line contains a non-empty string.
- Input ends when **EOF (End of File)** is encountered.

---

## Output Format

For every input line, print:

```text
lineNumber lineContent
```

where:

- `lineNumber` starts from **1**.
- `lineContent` is the corresponding input line.

---

## Example

### Input

```text
Hello world
I am a file
Read me until end-of-file.
```

### Output

```text
1 Hello world
2 I am a file
3 Read me until end-of-file.
```

---

## Explanation

Since the number of input lines is unknown, the program keeps reading lines until **EOF** is reached. Each line is printed along with its corresponding line number.

In Java, EOF can be handled using:

```java
while (scanner.hasNextLine()) {
    // Read and process each line
}
```

The loop automatically terminates when there are no more lines to read.

---
