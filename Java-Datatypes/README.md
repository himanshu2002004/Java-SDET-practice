# Java Datatypes

## Problem Statement

Java provides four primitive data types for storing integer values: **byte**, **short**, **int**, and **long**. Each data type has a fixed range of values it can store.

Given an integer **n**, determine which of these primitive data types can store the given value.

If the number fits in one or more data types, print all applicable data types in the following order:

- byte
- short
- int
- long

If the number cannot be stored in any of these data types, print that it **can't be fitted anywhere**.

---

## Input Format

- The first line contains an integer **T**, representing the number of test cases.
- Each of the next **T** lines contains an integer **n**.

---

## Output Format

For each test case:

- If the number can be stored, print:

```text
n can be fitted in:
* byte
* short
* int
* long
```

Print only the data types that can store the given number.

- Otherwise, print:

```text
n can't be fitted anywhere.
```

---

## Constraints

- The input integer may be arbitrarily large or small.

---

## Example

### Input

```text
5
-150
150000
1500000000
213333333333333333333333333333333333
-100000000000000
```

### Output

```text
-150 can be fitted in:
* short
* int
* long
150000 can be fitted in:
* int
* long
1500000000 can be fitted in:
* int
* long
213333333333333333333333333333333333 can't be fitted anywhere.
-100000000000000 can be fitted in:
* long
```

---

## Explanation

The program checks whether each input value falls within the range of Java's primitive integer data types:

| Data Type | Size | Range |
|-----------|------|---------------------------------------------|
| `byte` | 8-bit | -128 to 127 |
| `short` | 16-bit | -32,768 to 32,767 |
| `int` | 32-bit | -2,147,483,648 to 2,147,483,647 |
| `long` | 64-bit | -9,223,372,036,854,775,808 to 9,223,372,036,854,775,807 |

If the value exceeds the range of `long`, it cannot be stored in any primitive integer data type.
