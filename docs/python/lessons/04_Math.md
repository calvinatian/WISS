---
layout: default
title: Math
---

# Math

Using python we can perform arithmetic operations such as addition or division. The basic operators are:

- `+` for addition
- `-` for subtraction
- `*` for multiplication
- `/` for division

Another special operator is the modulus argument `%`. What is a modulus? A modulus in python returns the remainder. For example:

```python
9 % 3
# returns 0
8 % 3
# returns 2
```

- 9 divided by 3 has no remainder so the modulus returns 0.
- 8 divided by 3 has a remainder of 2 so the modulus returns 2.
- You might notice we used a `#` symbol to make a comment in the code. A comment is not ignored when the program runs and is useful to make notes in the code itself.

What can we do with these operators? Well with integers and floats we can perform basic math like you would expect from a calculator. But some of these operators can also be used on strings (addition and multiplication).

When we add two strings together we are combining them into a single string. For example:

```python
var1 = "hello"
var2 = "world"
var3 = var1 + var2
print(var3)
# This will print "helloworld"

var4 = var1 * 3
print(var4)
# This will print "hellohellohello"
```

You can see when we add two strings we get a new string with the combination of the strings used. And when we multiply a string by an integer we get the same string repeated however many times. *note you cannot multiply a string by a float*
