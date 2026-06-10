
# Identifiers in Python

An **Identifier** is a name used to identify a variable, function, class, module, or object in a Python program.

# Example

```python
a = 10
name = "Raja"
```

Identifiers can be:

- Variable Names
- Function Names
- Class Names
- Module Names


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

# Reserved Words (Keywords) in Python

## What are Reserved Words?

In Python, some words are reserved to represent predefined meanings or functionality. These words are called **Reserved Words** or **Keywords**.

Keywords cannot be used as identifiers (variable names, function names, class names, etc.).

### Example

❌ Invalid

```python
if = 10
```

✅ Valid

```python
value = 10
```

---

## Python Reserved Words

### Boolean and Special Values

```python
True
False
None
```

### Logical Operators

```python
and
or
not
is
```

### Conditional Statements

```python
if
elif
else
```

### Loops and Control Statements

```python
while
for
break
continue
return
in
yield
```

### Exception Handling

```python
try
except
finally
raise
assert
```

### Functions, Classes, and Modules

```python
import
from
as
class
def
pass
global
nonlocal
lambda
del
with
```

---

## Important Notes

### 1. Keywords Contain Only Alphabetic Characters

All Python keywords contain only alphabet symbols.

### 2. Most Keywords Are Lowercase

The following three keywords begin with uppercase letters:

```python
True
False
None
```

Example:

❌ Invalid

```python
a = true
```

✅ Valid

```python
a = True
```

---

## Display All Python Keywords

Python provides the `keyword` module to view all reserved words.

```python
import keyword

print(keyword.kwlist)
```

### Output

```python
['False', 'None', 'True', 'and', 'as', 'assert',
 'break', 'class', 'continue', 'def', 'del',
 'elif', 'else', 'except', 'finally', 'for',
 'from', 'global', 'if', 'import', 'in',
 'is', 'lambda', 'nonlocal', 'not', 'or',
 'pass', 'raise', 'return', 'try', 'while',
 'with', 'yield']
```

---

## Check Whether a Word Is a Keyword

```python
import keyword

print(keyword.iskeyword("for"))
print(keyword.iskeyword("raja"))
```

### Output

```text
True
False
```

---

## Practice Questions

### Theory

1. What are reserved words in Python?
2. Why can't reserved words be used as identifiers?
3. Name the three keywords that start with uppercase letters.
4. What is the purpose of the `keyword` module?
5. Differentiate between `is` and `==`.

### Coding Practice

#### Question 1

Display all Python keywords.

```python
import keyword

print(keyword.kwlist)
```

#### Question 2

Find the total number of Python keywords.

```python
import keyword

print(len(keyword.kwlist))
```

#### Question 3

Check whether a given word is a keyword.

```python
import keyword

word = input("Enter a word: ")

if keyword.iskeyword(word):
    print("Keyword")
else:
    print("Not a Keyword")
```

---
---
