---

# Identifiers in Python

An Identifier is a name used to identify a variable, function, class, module, or any other object in a Python program.

### Examples

python a = 10          # Variable student_name = "Raja" 

Identifiers can be:

- Variable Names
- Function Names
- Class Names
- Module Names
- Object Names

---

## Rules for Defining Identifiers

### 1. Allowed Characters

Python identifiers can contain:

- Alphabets (A-Z, a-z)
- Digits (0-9)
- Underscore ()

#### Valid Examples

python total = 100 student1 = "Raja" _emp = "John" 

#### Invalid Example

python ca$h = 100 

Reason: Dollar ($) symbol is not allowed in Python identifiers.

---

### 2. Identifier Should Not Start with a Digit

#### Invalid

python 123total = 100 

#### Valid

python total123 = 100 

---

### 3. Identifiers are Case Sensitive

Python treats uppercase and lowercase letters differently.

python total = 10 TOTAL = 999  print(total)   # 10 print(TOTAL)   # 999 

---

### 4. Reserved Keywords Cannot Be Used

Python keywords cannot be used as identifiers.

#### Invalid

python def = 10 

Examples of keywords:

python if else for while def class return import 

---

### 5. No Length Limit

Python does not impose a strict length limit on identifiers.

python this_is_a_very_long_variable_name_used_for_demonstration = 100 

However, very long names are not recommended.

---

### 6. Dollar ($) Symbol is Not Allowed

#### Invalid

python cash$amount = 1000 

---

## Special Meaning of Underscore ()

### Single Underscore (name)

Indicates a private identifier by convention.

python _name = "Raja" 

---

### Double Underscore (__name)

Indicates a strongly private identifier inside classes.

python __salary = 50000 

---

### Double Underscore at Both Ends (name)

These are special language-defined names, also known as Magic Methods or Dunder Methods.

Examples:

python __init__ __str__ __add__ 

---

## Valid and Invalid Identifiers

| Identifier | Valid/Invalid |
|------------|--------------|
| 123total | ❌ Invalid |
| total123 | ✅ Valid |
| JavaShare | ✅ Valid |
| ca$h | ❌ Invalid |
| abc_abc | ✅ Valid |
| def | ❌ Invalid |
| i | ✅ Valid |

---

## Practice Questions

### Theory

1. What is an Identifier?
2. What characters are allowed in Python identifiers?
3. Why are identifiers case-sensitive?
4. Can a Python identifier start with a digit?
5. What is the purpose of underscore () in identifiers?

### Coding Practice

1. Create three valid identifiers.
2. Create three invalid identifiers and explain why they are invalid.
3. Demonstrate case sensitivity using two variables.
4. Create variables using single and double underscores.
5. Display values stored in different identifiers.
```
:::

This section fits naturally as Chapter 2: Identifiers in Python after the introduction chapter in your README.