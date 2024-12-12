---
layout      : post
title       : "What are Python Operators?"
date        : 2024-12-11
author      : charishma_sirigiri
categories  : [Programming]
tags        : [Coding, Python]

---

## *Introduction*

Python operators are special symbols or keywords used to perform operations on variables and values. They are fundamental in executing tasks such as mathematical calculations, comparisons, logical evaluations, and more. Understanding operators is essential for writing efficient and functional Python code.

---

## *Types of Python Operators*

### 1. **Arithmetic Operators**
Used for basic mathematical operations:
- `+` : Addition
- `-` : Subtraction
- `*` : Multiplication
- `/` : Division
- `%` : Modulus (remainder)
- `**` : Exponentiation (power)
- `//` : Floor division (quotient without remainder)

**Example:**
```python
a = 10
b = 3
print(a + b)  # Output: 13
print(a % b)  # Output: 1
```

---

### 2. **Comparison Operators**
Used to compare values:
- `==` : Equal to
- `!=` : Not equal to
- `>` : Greater than
- `<` : Less than
- `>=` : Greater than or equal to
- `<=` : Less than or equal to

**Example:**
```python
x = 5
y = 10
print(x > y)  # Output: False
```

---

### 3. **Logical Operators**
Used to combine conditional statements:
- `and` : Returns `True` if both statements are true.
- `or` : Returns `True` if at least one statement is true.
- `not` : Reverses the result (negation).

**Example:**
```python
is_student = True
has_id = False
print(is_student and has_id)  # Output: False
```

---

### 4. **Assignment Operators**
Used to assign values to variables:
- `=` : Assign
- `+=` : Add and assign
- `-=` : Subtract and assign
- `*=` : Multiply and assign
- `/=` : Divide and assign
- `//=` : Floor divide and assign
- `%=` : Modulus and assign
- `**=` : Exponentiation and assign

**Example:**
```python
count = 10
count += 5  # Equivalent to count = count + 5
print(count)  # Output: 15
```

---

### 5. **Bitwise Operators**
Operate at the binary level:
- `&` : AND
- `|` : OR
- `^` : XOR
- `~` : NOT
- `<<` : Left shift
- `>>` : Right shift

**Example:**
```python
a = 5  # Binary: 0101
b = 3  # Binary: 0011
print(a & b)  # Output: 1 (Binary: 0001)
```

---

### 6. **Membership Operators**
Used to test membership in sequences:
- `in` : Returns `True` if a value is in the sequence.
- `not in` : Returns `True` if a value is not in the sequence.

**Example:**
```python
fruits = ["apple", "banana", "cherry"]
print("banana" in fruits)  # Output: True
```

---

### 7. **Identity Operators**
Used to compare memory locations of two objects:
- `is` : Returns `True` if both variables refer to the same object.
- `is not` : Returns `True` if variables refer to different objects.

**Example:**
```python
x = [1, 2, 3]
y = [1, 2, 3]
print(x is y)  # Output: False
```

## *Operator Precedence*

Python follows specific rules for operator precedence, determining the order in which different operators are evaluated in an expression:

1. **Parentheses** `()`
2. **Exponentiation** `**`
3. **Unary operators** `+x`, `-x`, `~x`
4. **Multiplication/Division** `*`, `/`, `//`, `%`
5. **Addition/Subtraction** `+`, `-`
6. **Bitwise shifts** `>>`, `<<`
7. **Bitwise AND** `&`
8. **Bitwise XOR** `^`
9. **Bitwise OR** `|`
10. **Comparison operators** `==`, `!=`, `>`, `>=`, `<`, `<=`
11. **Logical operators** `not`, `and`, `or`

**Example:**
```python
result = 2 + 3 * 4  # Multiplication happens first
print(result)  # Output: 14
```

## *References*

1. [Python Official Documentation - Operators](https://docs.python.org/3/reference/operators.html)
2. [Real Python - Python Operators](https://realpython.com/python-operators-expressions/)

<iframe width="560" height="315" src="https://www.youtube.com/embed/tSP3jWnx5ZY" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


---

## *Conclusion*

Operators are the building blocks of Python programming. Mastering them allows you to write more powerful and concise code. From basic arithmetic to advanced bitwise operations, Python operators provide the tools necessary for efficient manipulation of data and logic.

---
