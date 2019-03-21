# Inputs

Sometimes when a program runs we want the user to input some data manually. This can be achieved with the `input()` function.

```python
prompt = input('Enter a number: ')
print(prompt)
```

In the example above we create a variable named prompt and assign a value based on what the user inputs. The stuff in quotation marks is what is shown to the user when the program runs.

In the above example you might notice we ask for a number. But what if the user inputs a string? How do we perform data validation to make sure the type of data the user inputs is what we want?

But before that, what is the type of data when the user inputs a number? You may remember previously about different data types such as strings, integers, and floats. We can check the data type of a variable with the `type()` function. The word inside the brackets is the variable or item to check. In the example below we are checking the data type of the variable `prompt`. Similarly, there is also the `string()` function to turn numbers into strings.

```python
type(prompt)
```

If you try it for yourself, you may be surprised to see it is a string. Everything the user inputs is classified as a string. And a string value of `"3"` is very different from an integer value of `3` and different from a float value of `3.0`. So how do we turn a numerical answer like `"3"` from a string into an integer or float? Using the `int()` and `float()` functions.

```python
prompt = int(prompt)
prompt = float(prompt)
```

Now we set the variable `prompt` to equal the integer value of `prompt` and then set it to the float value. You can test for yourself using the `type()` function. But what happens when we try to use the `int()` or `float()` function on a string that cannot be turned into an integer or float such as `"hello world"`? Try for yourself and see what happens.

## String concatenation

String concatenation is just a fancy word for joining two or more strings together. You may remember last lesson we can use the addition `+` operator on two strings to join them together into a new string. Make use of this to join a string together to print in the exercise below.

## Exercise

In this exercise you will need to ask for the user for their name and then print out a greeting addressed to that name. For example, if the user inputs `Bob` then the program should print out `Hello Bob!`.