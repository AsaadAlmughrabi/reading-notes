
## File Handling in Python

### Introduction
A file is a named location used for storing data. Python provides various functions to perform different file operations, known as File Handling.

### Methods of Handling Files

1. **read() Method**:
    - Example:
      ```python
      file1 = open("file1.txt")
      ```
   This method opens a file for reading.

2. **write() Method**:
    - To write to a Python file (overwrite), open it in write mode using the `'w'` parameter.
      ```python
      # open the file2.txt in write mode
      file2 = open('file2.txt', 'w')
      # write contents to the file2.txt file
      file2.write('Programming is Fun.\n')
      file2.write('Programiz for beginners\n')
      ```

3. **close() Method**:
    - Use `close()` to close the file when done.

### Opening a Python File Using `with...open`

There is a better way to open a file using `with...open`. This automatically closes the file after use.
```python
with open("file1.txt", "r") as file1:
    read_content = file1.read()
    print(read_content)
```

## Exception Handling in Python

### Introduction
Exception handling in Python is a mechanism to manage runtime errors that occur during program execution. It allows developers to gracefully handle unexpected situations, preventing the program from crashing.

### Types of Errors

1. **SyntaxError**:
   - Occurs when the Python interpreter encounters a syntax error in the code.
   
2. **IndentationError**:
   - Occurs when there is incorrect indentation in the code.
   
3. **NameError**:
   - Occurs when a variable or function name is not found in the current scope.
   
4. **TypeError**:
   - Occurs when an operation is performed on an object of inappropriate type.
   
5. **ValueError**:
   - Occurs when a built-in operation or function receives an argument with the right type but an inappropriate value.
   
6. **ZeroDivisionError**:
   - Occurs when attempting to divide a number by zero.
   
7. **FileNotFoundError**:
   - Occurs when trying to open or access a file that does not exist.
   
8. **IOError**:
   - Occurs when an input/output operation fails, such as reading from or writing to a file.

### Handling Exceptions

Exception handling in Python involves using `try...except` blocks to catch and handle exceptions. Here's how it works:

```python
try:
    # code that may raise an exception
except SomeExceptionType:
    # code to handle the exception
```

- The `try` block contains the code that may raise an exception.
- If an exception occurs, the corresponding `except` block is executed. You can specify the type of exception to catch by including the exception class after the `except` keyword.
- Multiple `except` blocks can be used to catch different types of exceptions.
- Optionally, you can include an `else` block after the `except` blocks to execute code if no exceptions occur in the `try` block.
- The `finally` block, if provided, is always executed regardless of whether an exception occurs. It is typically used for cleanup operations, such as closing files or releasing resources.

