# Python 3.12 symbols

### **Comments**

| **Symbol** | **Purpose**               |
|------------|---------------------------|
| `#`        | Single-line comment.       |
| `''' '''`  | Multi-line string, often used for multi-line comments.        |

### **Imports and Modules**

| **Symbol** | **Purpose**                                          |
|------------|------------------------------------------------------|
| `import`   | Imports a module.                                    |
| `from`     | Imports specific parts from a module.                |
| `as`       | Renames an imported module or variable.              |

### **Variable Declaration and Assignment**

| **Symbol** | **Purpose**                                       |
|------------|---------------------------------------------------|
| `=`        | Assigns a value to a variable.                    |
| `:=`       | Assignment expression (walrus operator), used within expressions. |

### **Data Types and Structures**

| **Symbol** | **Purpose**                                         |
|------------|-----------------------------------------------------|
| `int`      | Integer data type.                                  |
| `float`    | Floating-point data type.                           |
| `str`      | String data type.                                   |
| `list`     | List data type, a mutable sequence of elements.     |
| `tuple`    | Tuple data type, an immutable sequence of elements. |
| `dict`     | Dictionary data type, a collection of key-value pairs. |
| `set`      | Set data type, an unordered collection of unique elements. |
| `frozenset`| Immutable version of a set.                        |
| `bool`     | Boolean data type (`True` or `False`).              |
| `None`     | Represents a null value or no value at all.         |

### **Functions and Control Flow**

| **Symbol**  | **Purpose**                                                      |
|-------------|------------------------------------------------------------------|
| `def`       | Declares a function.                                             |
| `return`    | Exits a function and optionally returns a value.                 |
| `lambda`    | Declares an anonymous function.                                  |
| `yield`     | Used in a generator function to return a value without exiting.  |
| `if`        | Conditional statement.                                           |
| `elif`      | Else-if statement, follows an `if`.                              |
| `else`      | Specifies an alternative block of code if no `if` or `elif` conditions are met. |
| `for`       | Loop that iterates over a sequence.                              |
| `while`     | Loop that continues as long as a condition is `True`.            |
| `break`     | Exits the nearest enclosing loop.                                |
| `continue`  | Skips the rest of the current loop iteration and continues with the next iteration. |
| `pass`      | A null operation, often used as a placeholder.                   |
| `with`      | Simplifies exception handling by encapsulating common preparation and cleanup tasks. |
| `async`     | Declares an asynchronous function.                               |
| `await`     | Waits for an asynchronous function to complete.                  |

### **Classes and Object-Oriented Programming**

| **Symbol**  | **Purpose**                                               |
|-------------|-----------------------------------------------------------|
| `class`     | Declares a class.                                          |
| `self`      | Refers to the instance of the class.                       |
| `__init__`  | The initializer method for a class (constructor).          |
| `super()`   | Calls a method from a parent class.                        |
| `@classmethod` | Declares a class method.                                |
| `@staticmethod` | Declares a static method.                              |
| `@property` | Declares a method as a property.                           |

### **Operators**

| **Symbol**  | **Purpose**                                         |
|-------------|-----------------------------------------------------|
| `+`         | Adds numbers, concatenates strings, or merges lists.|
| `-`         | Subtracts numbers.                                  |
| `*`         | Multiplies numbers or repeats sequences.            |
| `/`         | Divides numbers (float division).                   |
| `//`        | Floor division.                                     |
| `%`         | Modulus operator, returns the remainder of division.|
| `**`        | Exponentiation.                                     |
| `=`         | Assigns a value to a variable.                      |
| `==`        | Checks if two values are equal.                     |
| `!=`        | Checks if two values are not equal.                 |
| `<`         | Less than comparison.                               |
| `>`         | Greater than comparison.                            |
| `<=`        | Less than or equal to comparison.                   |
| `>=`        | Greater than or equal to comparison.                |
| `and`       | Logical AND.                                        |
| `or`        | Logical OR.                                         |
| `not`       | Logical NOT.                                        |
| `is`        | Checks if two variables refer to the same object.   |
| `in`        | Checks if a value is present in a sequence or collection. |
| `<<`        | Bitwise left shift.                                 |
| `>>`        | Bitwise right shift.                                |
| `&`         | Bitwise AND.                                        |
| `|`         | Bitwise OR.                                         |
| `^`         | Bitwise XOR.                                        |
| `~`         | Bitwise NOT.                                        |
| `+`         | Addition or concatenation.                          |
| `-`         | Subtraction.                                        |
| `*`         | Multiplication or repetition.                       |

### **Collections and Iteration**

| **Symbol** | **Purpose**                                               |
|------------|-----------------------------------------------------------|
| `[]`       | List or index/slice operator.                             |
| `()`       | Tuple or function call operator.                          |
| `{}`       | Dictionary or set.                                        |
| `:`        | Slicing operator or key-value separator in dictionaries.  |
| `,`        | Separates elements in a list, tuple, or function arguments. |
| `...`      | Ellipsis, used as a placeholder or for slicing multidimensional arrays. |
| `zip()`    | Combines two or more iterables into tuples.               |
| `enumerate()` | Adds a counter to an iterable.                         |
| `range()`  | Generates a sequence of numbers.                          |

### **Error Handling**

| **Symbol**  | **Purpose**                                          |
|-------------|------------------------------------------------------|
| `try`       | Defines a block of code to test for errors.          |
| `except`    | Catches and handles exceptions raised in the `try` block. |
| `else`      | Defines a block of code to be executed if no exceptions are raised. |
| `finally`   | Defines a block of code that will be executed no matter what. |
| `raise`     | Raises an exception manually.                        |
| `assert`    | Tests if a condition is true, raises `AssertionError` if not. |

### **Context Management**

| **Symbol**  | **Purpose**                                     |
|-------------|-------------------------------------------------|
| `with`      | Used for resource management and cleanup actions. |
| `as`        | Binds a name to the result of the context expression. |

### **Miscellaneous**

| **Symbol** | **Purpose**                                      |
|------------|--------------------------------------------------|
| `None`     | Represents a null value or no value at all.      |
| `_`        | Used as a throwaway variable in loops or functions. |
| `__name__` | Indicates the name of the module being executed. |
| `__main__` | Indicates the entry point of the program.        |
| `global`   | Declares a global variable.                      |
| `nonlocal` | Declares a variable in the nearest enclosing scope that is not global. |
