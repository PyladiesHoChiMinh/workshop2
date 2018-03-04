### Pyladies Workshop 2: Variables and simple data types
---
Welcome to the second workshop of Pyladies - Ho Chi Minh chapter. This time we will continue to learn more about Python by starting with simple examples and working in pairs to help each other understand instruction and complete excercise. Most of content in this workshop is adapted from "Python Crash Course: A Hands-on, Project-based Introduction to Programming" by Eric Matthes and "Developer Class" in `python 3`.

Feel free to reach out to us if you have any question.

#### Outline
0. Zen of Python
1. Examples of variables
2. How to name and use variable
3. Understand String
4. Understand Number
5. Combine String and numbers
6. Review

### Zen of Python

Pythonistas, a Pythonic way to called Python users, love simplicity and readability. Our philosophy is that the code should be beautiful and elegant. Try to run the following code to get a `The Zen of Python` by Tim Peters
```python

import this

```

One of the most important take-away notices for you is that

```
Now is better than never
```

Again, we would emphasize that the best way to learn and practice Python is starting with a simple and workable code for any project rather waiting until learning every details but never know when it would end. That's why Pyladies is here to help :)

### What are variables and some examples

Let us illustrate how to use a variable in by a very simple program.

```python

message = "Hello Python world!"
# Notice: in PEP8, double quotes are used for human reading
print(message)
```

Run the above in your `Jupyter Lab` and let us know what happens. To explain, we have already created a variable named `message`. In general, each variable is associated to a value. In this example, `"Hello Python world!"` is a `string` attached to  `message`. And if you change a value of variable, it will be updated the newest.

### How to name and use variables

Some rules to help you

- Names of variable can contain letters, numbers and underscores. However, numbers and score can not used at the beginning of variable. For example,  `message_1`, but NOT `1_message`

- We don't use space, instead underscore. For example, `message_1`, but NOT  `message 1`

- Avoid using Python keywords or function names, unless a new value will linked. For example, do not use `list` to name a list of things. Use an descriptive names, such as `list_of_words`

- Following the above idea, please use names which is informative, not representative such as `message_id` rather than  `id`

- Note: In PEP8, we use lower case for name of variables such as `message_id`, `new_message`. It will be fine if you use upper case, however, the reason why we make this regularization is for a sake of common style.


### Understand string

String is simply defined as a series of characters enclosed by a pair special characters. Indeed, there are three of them, e.g. `"`, `"`, and `"""` with respect to double quotes, astrophes and triple quote. So, what is a difference

```python

"Hello! I am a pythonista."
'Hello! I am a pythonista.'
```

### Understand numbers

Integers and floats are the most basic data types in `python` allowing you to work on multiplication (`+`), subtract (`-`), multiply (`*`) and division (`/`). For integers, you can make operations with exponential (`**`) and modular (`%`) and residue (`//`). Let us do some fun calculations

```python

```

#### Combine String and numbers

See this example, and tell us why it is wrong

```python
year = 2018
message = "Happy year of " + year
print(message)
```
How to fix this


```python
year = 2018
message = "Happy year of " + str(year)
print(message)
```

### Review

In the previous, you have gone through some of important aspects of `Python` with `variable` and two simple data type such as `string` and `number`. Let us do a small quiz to test our knowledge before moving to a pair-programming assignment
