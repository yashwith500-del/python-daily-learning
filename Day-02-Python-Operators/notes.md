# Day 02 — Python Operators

## 📚 What I Learned

Today I learned about **operators in Python**. Operators are symbols or keywords used to perform operations on values and variables.

### 1. Arithmetic Operators

Used for mathematical calculations.

| Operator | Operation | Example |
|---|---|---|
| `+` | Addition | `10 + 5` |
| `-` | Subtraction | `10 - 5` |
| `*` | Multiplication | `10 * 5` |
| `/` | Division | `10 / 5` |
| `//` | Floor Division | `10 // 3` |
| `%` | Modulus / Remainder | `10 % 3` |
| `**` | Exponentiation | `10 ** 2` |

Example:

```python
a = 10
b = 3

print(a + b)
print(a - b)
print(a * b)
print(a / b)
print(a // b)
print(a % b)
print(a ** b)
```

### 2. Comparison Operators

Used to compare two values. The result is either `True` or `False`.

| Operator | Meaning |
|---|---|
| `==` | Equal to |
| `!=` | Not equal to |
| `>` | Greater than |
| `<` | Less than |
| `>=` | Greater than or equal to |
| `<=` | Less than or equal to |

Example:

```python
a = 10
b = 5

print(a > b)
print(a == b)
print(a != b)
```

### 3. Logical Operators

Used to combine or modify conditions.

- `and` — True when both conditions are True.
- `or` — True when at least one condition is True.
- `not` — Reverses the Boolean result.

Example:

```python
age = 20

print(age > 18 and age < 30)
print(age < 18 or age == 20)
print(not(age > 18))
```

### 4. Assignment Operators

Used to assign and update values.

| Operator | Example | Equivalent to |
|---|---|---|
| `=` | `x = 10` | `x = 10` |
| `+=` | `x += 5` | `x = x + 5` |
| `-=` | `x -= 5` | `x = x - 5` |
| `*=` | `x *= 5` | `x = x * 5` |
| `/=` | `x /= 5` | `x = x / 5` |

Example:

```python
x = 10
x += 5

print(x)
```

### 5. Membership Operators

Used to check whether a value exists in a sequence.

- `in`
- `not in`

Example:

```python
name = "Python"

print("P" in name)
print("z" not in name)
```

## 📝 Practice

1. Write a program using arithmetic operators.
2. Compare two numbers using comparison operators.
3. Write examples using `and`, `or`, and `not`.
4. Practice updating a variable using assignment operators.
5. Check whether a character exists in a string using `in`.

## 🔍 What I Understood

I learned how Python operators can be used for calculations, comparisons, logical conditions, assigning and updating values, and checking whether a value exists in a sequence.

## 🚀 Next Topic

**Day 03 — Continue with the remaining Python operators or the next topic taught in class.**
