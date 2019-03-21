# If Statements

Often when coding we will want to run a portion of code only when a certain condition is met. The so called if-then statements. *If this condition is true, then run this code.* In python this is achieved with the aptly named `if` statements. Take a look at the code below.

```python
var = input("Input the password: ")
if var == "secret":
    print("Access granted.")
else:
    print("Invalid")
```

First, we ask the user to input a password. If what the user inputs is equal to our true condition, in this case the phrase "secret", then the program will print out `Access granted.` All other inputs will result in the program printing out `Invalid`.

You may notice we used two equal signs to check if the input password is equal to what we want. You might remember when we set the value of variables we use one equals sign. So 2 are needed if we want to perform a check instead. Along with `=`, other equality checks can also be used such as less than `<` and greater than `>`. To do greater than or equal to use a combination of the greater than sign and equals sign `<=`. To check if something is not equal use the `!=` symbols.

The `else` statement in the code above is sort of the default "fallback" if nothing matches correctly. It is not explicitly needed byt recommended. You can combine multiple if statements together using `elif`. For example, we can add onto the code above using another check with the `elif` command.

```python
var = input("Input the password: ")
if var == "secret":
    print("Access granted.")
elif var == "password":
    print("Incorrect")
else:
    print("Invalid")
```

Note the syntax used in the program. After the if statement you must use the colon `:` symbol and have what you want to run after on a new indented line. Unlike other programming languages python utilizes whitespace, or invisible characters such as spaces. Without indentation you will run into syntax errors.

## Exercise

Make a password lock like the example above but instead of using a string as the passphrase use a float.