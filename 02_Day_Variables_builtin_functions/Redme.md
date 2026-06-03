---

# Identifiers in Python

An **Identifier** is a name used to identify a variable, function, class, module, or object in a Python program.

## Example

```python
a = 10
name = "Raja"
```

Identifiers can be:

- Variable Names
- Function Names
- Class Names
- Module Names

---

## Rules for Defining Identifiers

### 1. Allowed Characters

Python identifiers can contain:

- Alphabets (A-Z, a-z)
- Digits (0-9)
- Underscore (_)

#### Valid Examples

```python
total = 100
student1 = "Raja"
_emp = "John"
```

#### Invalid Example

```python
ca$h = 100
```

Output:

```text
SyntaxError: invalid syntax
```

---

### 2. Identifier Should Not Start with a Digit

❌ Invalid

```python
123total = 100
```

✅ Valid

```python
total123 = 100
```

---

### 3. Identifiers are Case Sensitive

```python
total = 10
TOTAL = 999

print(total)
print(TOTAL)
```

Output:

```text
10
999
```

---

### 4. Reserved Keywords Cannot Be Used as Identifiers

❌ Invalid

```python
def = 10
```

Examples of Python keywords:

```python
if
else
for
while
def
class
return
import
```

---

### 5. No Length Limit

```python
this_is_a_very_long_variable_name_used_for_demonstration = 100
```

Although valid, shorter meaningful names are recommended.

---

### 6. Dollar Symbol ($) is Not Allowed

❌ Invalid

```python
cash$amount = 1000
```

---

## Special Meaning of Underscore (_)

### Single Underscore

```python
_name = "Raja"
```

Indicates a private identifier by convention.

---

### Double Underscore

```python
__salary = 50000
```

Indicates a strongly private identifier inside classes.

---

### Magic Methods (Dunder Methods)

Identifiers that start and end with double underscores are special Python methods.

```python
__init__
__str__
__add__
__len__
```

---

## Valid and Invalid Identifiers

| Identifier | Status |
|------------|---------|
| 123total | ❌ Invalid |
| total123 | ✅ Valid |
| JavaShare | ✅ Valid |
| ca$h | ❌ Invalid |
| _abc_abc_ | ✅ Valid |
| def | ❌ Invalid |
| i | ✅ Valid |

---

## Practice Questions

### Theory

1. What is an Identifier?
2. What characters are allowed in Python identifiers?
3. Why are identifiers case-sensitive?
4. Can an identifier start with a digit?
5. What is the purpose of underscore (_) in Python?

### Coding Practice

#### Question 1

Create valid identifiers and print their values.

```python
student_name = "Raja"
age = 25
_course = "Python"

print(student_name)
print(age)
print(_course)
```

#### Question 2

Demonstrate case sensitivity.

```python
name = "Python"
NAME = "Programming"

print(name)
print(NAME)
```

#### Question 3

Create five valid identifiers and two invalid identifiers.

```python
# Valid
employee_id = 101
salary = 50000
_city = "Bhopal"

# Invalid
# 123name = "Raja"
# ca$h = 100
```

---