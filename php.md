# PHP Symbols

### **Comments**

| **Symbol** | **Purpose**               |
|------------|---------------------------|
| `//`       | Single-line comment.       |
| `#`        | Single-line comment (alternative syntax). |
| `/* */`    | Multi-line comment.        |

### **Variables and Constants**

| **Symbol** | **Purpose**                                       |
|------------|---------------------------------------------------|
| `$`        | Prefix for variables.                             |
| `define()` | Defines a constant.                               |
| `const`    | Declares a constant inside classes.               |

### **Data Types**

| **Symbol** | **Purpose**                                         |
|------------|-----------------------------------------------------|
| `int`      | Integer data type.                                  |
| `float`    | Floating-point data type.                           |
| `string`   | String data type.                                   |
| `array`    | Array data type, a collection of key-value pairs.   |
| `object`   | Object data type, an instance of a class.           |
| `bool`     | Boolean data type (`true` or `false`).              |
| `null`     | Represents a null value or no value at all.         |
| `callable` | Represents a function that can be called.          |
| `iterable` | Represents an array or an object that can be iterated over. |

### **Functions and Control Flow**

| **Symbol**  | **Purpose**                                               |
|-------------|-----------------------------------------------------------|
| `function`  | Declares a function.                                       |
| `return`    | Exits a function and optionally returns a value.           |
| `global`    | Declares a global variable inside a function.              |
| `static`    | Declares a static variable or method.                      |
| `if`        | Conditional statement.                                     |
| `elseif`    | Else-if statement, follows an `if`.                        |
| `else`      | Specifies an alternative block of code if no `if` or `elseif` conditions are met. |
| `switch`    | Selects among multiple branches.                           |
| `case`      | A branch in a `switch` statement.                          |
| `default`   | The default branch in a `switch` statement if no other `case` matches. |
| `for`       | Loop that iterates over a sequence.                        |
| `foreach`   | Loop that iterates over elements in an array or object.    |
| `while`     | Loop that continues as long as a condition is `true`.      |
| `do`        | Executes a loop at least once before checking the condition. |
| `break`     | Exits a loop or `switch` statement.                        |
| `continue`  | Skips the rest of the current loop iteration and continues with the next iteration. |
| `goto`      | Jumps to a labeled statement within the same function.     |
| `yield`     | Returns a value from a generator function without exiting. |
| `include`   | Includes and evaluates a specified file.                   |
| `include_once` | Includes a file only once, even if called multiple times. |
| `require`   | Includes a file, but throws a fatal error if the file is missing. |
| `require_once` | Includes a file only once, similar to `include_once` but throws a fatal error if missing. |

### **Classes and Object-Oriented Programming**

| **Symbol**  | **Purpose**                                               |
|-------------|-----------------------------------------------------------|
| `class`     | Declares a class.                                          |
| `extends`   | Inherits properties and methods from a parent class.       |
| `implements`| Implements an interface.                                   |
| `public`    | Declares a public property or method (accessible from anywhere). |
| `protected` | Declares a protected property or method (accessible from the class and subclasses). |
| `private`   | Declares a private property or method (accessible only within the class). |
| `abstract`  | Declares an abstract class or method (must be implemented in subclasses). |
| `final`     | Declares a class or method that cannot be extended or overridden. |
| `interface` | Declares an interface.                                     |
| `trait`     | Declares a trait, a mechanism for code reuse in single inheritance. |
| `__construct()` | The constructor method for a class, called when an object is instantiated. |
| `__destruct()` | The destructor method for a class, called when an object is destroyed. |
| `__clone()`    | The clone method, called when an object is cloned.     |
| `__toString()` | Called when an object is treated as a string.           |
| `self`         | Refers to the current class.                            |
| `parent`       | Refers to the parent class.                             |
| `$this`        | Refers to the current object instance.                  |

### **Operators**

| **Symbol**  | **Purpose**                                         |
|-------------|-----------------------------------------------------|
| `+`         | Adds numbers or concatenates strings.               |
| `-`         | Subtracts numbers.                                  |
| `*`         | Multiplies numbers.                                 |
| `/`         | Divides numbers.                                    |
| `%`         | Modulus operator, returns the remainder of division.|
| `**`        | Exponentiation.                                     |
| `=`         | Assigns a value to a variable.                      |
| `==`        | Checks if two values are equal.                     |
| `!=`        | Checks if two values are not equal.                 |
| `<`         | Less than comparison.                               |
| `>`         | Greater than comparison.                            |
| `<=`        | Less than or equal to comparison.                   |
| `>=`        | Greater than or equal to comparison.                |
| `===`       | Checks if two values are identical (equal and same type). |
| `!==`       | Checks if two values are not identical.             |
| `and`       | Logical AND.                                        |
| `or`        | Logical OR.                                         |
| `xor`       | Logical XOR.                                        |
| `!`         | Logical NOT.                                        |
| `&&`        | Logical AND with higher precedence.                 |
| `\|\|`        | Logical OR with higher precedence.                  |
| `.`         | Concatenates two strings.                           |
| `&`         | Bitwise AND.                                        |
| `\|`         | Bitwise OR.                                         |
| `^`         | Bitwise XOR.                                        |
| `~`         | Bitwise NOT.                                        |
| `<<`        | Bitwise left shift.                                 |
| `>>`        | Bitwise right shift.                                |
| `->`        | Accesses an object's property or method.            |
| `::`        | Accesses static methods or properties, and constants. |
| `[]`        | Array declaration or access operator.               |
| `=>`        | Used in array declarations to separate keys and values. |

### **Arrays and Collections**

| **Symbol**  | **Purpose**                                               |
|-------------|-----------------------------------------------------------|
| `[]`        | Declares an array or accesses an array element.           |
| `array()`   | Declares an array (alternative syntax).                   |
| `list()`    | Assigns variables as if they were an array.               |
| `foreach`   | Loop that iterates over elements in an array or object.   |
| `isset()`   | Checks if a variable is set and is not `null`.            |
| `unset()`   | Destroys the specified variables or array elements.       |
| `empty()`   | Checks whether a variable is empty.                       |
| `array_merge()` | Merges one or more arrays.                            |
| `array_keys()`  | Returns all the keys of an array.                     |
| `array_values()`| Returns all the values of an array.                   |
| `array_push()`  | Adds one or more elements to the end of an array.     |
| `array_pop()`   | Removes the last element from an array.               |

### **Error Handling**

| **Symbol**  | **Purpose**                                              |
|-------------|----------------------------------------------------------|
| `try`       | Defines a block of code to test for exceptions.          |
| `catch`     | Catches and handles exceptions thrown in the `try` block. |
| `finally`   | Defines a block of code that will be executed no matter what. |
| `throw`     | Throws an exception manually.                            |
| `Exception` | The base class for all exceptions.                       |
| `Error`     | Represents a fatal error in PHP.                         |

### **Miscellaneous**

| **Symbol**       | **Purpose**                                                      |
|------------------|------------------------------------------------------------------|
| `echo`           | Outputs one or more strings.                                     |
| `print`          | Outputs a string (slower than `echo` and returns 1).             |
| `die()`          | Outputs a message and terminates the script.                     |
| `exit()`         | Terminates the script (similar to `die()` but without output).   |
| `include()`      | Includes and evaluates a specified file.                         |
| `require()`      | Includes a file, but throws a fatal error if the file is missing.|
| `include_once()` | Includes a file only once, even if called multiple times.        |
| `require_once()` | Includes a file only once, throws a fatal error if missing.      |
| `namespace`      | Declares a namespace to avoid name collisions.                   |
| `use`            | Imports a namespace, class, or function.                         |
| `__FILE__`       | The full path and filename of the file.                          |
| `__DIR__`        | The directory of the file.                                       |
| `__LINE__`       | The current line number in the file.                             |
| `__FUNCTION__`   | The function name.                                               |
| `__CLASS__`      | The class name.                                                  |
| `__METHOD__`     | The class method name.                                           |
| `__NAMESPACE__`  | The name of the current namespace.                               |
| `__TRAIT__`      | The name of the trait used in the current class.                 |
