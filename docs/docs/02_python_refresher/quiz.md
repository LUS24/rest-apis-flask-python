# Section 2 Quiz - A Python refresher

## Introduction

This quiz includes questions about all the subjects related to this second section. Some questions can be answered by reviewing the lecture and ebook but others will require you to do some research using Python documentation, StackOverflow, ChatGPT and/or other resouces.

1. What is the purpose of the Python extension in Visual Studio Code?
    - A) To write Python code in HTML
    - B) To add Python-specific features to Visual Studio Code
    - C) To convert Python code to JavaScript
    - D) To compile Python code to binary

Correct answer: B) To add Python-specific features to Visual Studio Code


2. How can you select a Python interpreter in Visual Studio Code?
    - A) By right-clicking on the Python file
    - B) By going to File -> Open
    - C) By pressing `Ctrl+Shift+P` and typing "Python: Select Interpreter"
    - D) By double-clicking on the Python file

Correct answer: C) By pressing `Ctrl+Shift+P` and typing "Python: Select Interpreter"


3. How do you assign a value to a variable in Python?

    - A) `variable == "value"`
    - B) `variable: "value"`
    - C) `variable = "value"`
    - D) `variable -> "value"`

Correct answer: C) `variable = "value"`

Explanation: In Python, the `=` operator is used to assign a value to a variable.


4. What happens if you try to reference a variable before it has been assigned a value?

    - A) Python assigns a default value to the variable
    - B) Python raises a `NameError`
    - C) Python ignores the reference
    - D) Python prompts the user to assign a value to the variable

Correct answer: B) Python raises a `NameError`

Explanation: If you try to reference a variable before it has been assigned a value, Python raises a `NameError` indicating that the variable is not defined.


5. Can the value of a variable change after it has been assigned?

    - A) Yes, variables in Python are mutable
    - B) No, variables in Python are immutable
    - C) Only if the variable is a string
    - D) Only if the variable is a number

Correct answer: A) Yes, variables in Python are mutable

Explanation: The value of a variable in Python can be changed after it has been assigned. This is why they are called "variables" - their content can vary.


6. What is the output of the following Python code 
    ```python
    name = "John"
    print(f"Hello, {name}!")
    ```
    - A) `Hello, {name}!`
    - B) `Hello, John!`
    - C) `Hello, name!`
    - D) `Hello, "John"!`

Correct answer: B) `Hello, John!`

Explanation: The f-string formatting in Python allows for embedding expressions inside string literals, using curly braces `{}`.


7. How do you get input from a user in Python?
    - A) `input("Enter your name: ")`
    - B) `print("Enter your name: ")`
    - C) `get("Enter your name: ")`
    - D) `read("Enter your name: ")`

Correct answer: A) `input("Enter your name: ")`

Explanation: The `input()` function is used to get input from the user in Python.


8. Which of the following is an immutable data type in Python?
    - A) List
    - B) Tuple
    - C) Set
    - D) All of the above

Correct answer: B) Tuple

Explanation: In Python, tuples are immutable, meaning they cannot be changed after they are created.


9. What are the two boolean values in Python?
    - A) True and False
    - B) 0 and 1
    - C) Yes and No
    - D) On and Off

Correct answer: A) True and False

Explanation: The two boolean values in Python are `True` and `False`.


10. What is the output of the following Python code?
    ```python
    x = 10
    if x > 5:
        print("x is greater than 5")
    ```
    - A) `x is greater than 5`
    - B) `x is less than 5`
    - C) No output
    - D) Error

Correct answer: A) `x is greater than 5`
Explanation: The `if` statement checks if the condition (in this case `x > 5`) is true. If it is, it executes the code within the `if` block.


11. What is the output of the following Python code?
    ```python
    x = [1, 2, 3, 4, 5]
    if 3 in x:
        print("3 is in the list")
    ```
    - A) `3 is in the list`
    - B) `3 is not in the list`
    - C) No output
    - D) Error

Correct answer: A) `3 is in the list`

Explanation: The `in` keyword in Python is used to check if a value is present in a sequence like a list.


12. What type of loop is this in Python?
    ```python
    for i in range(5):
        print(i)
    ```
    - A) While loop
    - B) For loop
    - C) Do-while loop
    - D) None of the above

Correct answer: B) For loop

Explanation: The `for` keyword in Python is used to create a `for` loop.


13. What is the output of the following Python code?
    ```python
    x = [i for i in range(5)]
    print(x)
    ```
    - A) `[0, 1, 2, 3, 4]`
    - B) `[1, 2, 3, 4, 5]`
    - C) `[5, 4, 3, 2, 1]`
    - D) `[4, 3, 2, 1, 0]`

Correct answer: A) `[0, 1, 2, 3, 4]`
Explanation: This is a list comprehension in Python. It creates a new list by iterating over the numbers from 0 to 4.


14. Given the following Python dictionary, how would you access the value associated with the key "name" and ensure that your code doesn't raise an exception, even if the key is not present in the dictionary?
    ```python
    person = {"name": "John", "age": 30}
    ```
    - A) `person["name"]`
    - B) `person.name`
    - C) `person(0)`
    - D) `person.get("name")`

Correct answer: D) `person.get("name")`
Explanation: While both `person["name"]` and `person.get("name")` can be used to access the value of a key in a Python dictionary, `person.get("name")` will return `None` instead of raising a `KeyError` if the key is not present in the dictionary. This makes it a safer option if you're not certain that the key exists.


15. What is the output of the following Python code?
    ```python
    x, y, z = (1, 2, 3)
    print(y)
    ```
    - A) `1`
    - B) `2`
    - C) `3`
    - D) Error

Correct answer: B) `2`

Explanation: This is an example of destructuring in Python. The values in the tuple on the right are unpacked into the variables on the left.