### **Comments**

| **Symbol** | **Purpose**               |
|------------|---------------------------|
| `//`       | Single-line comment.       |
| `/* */`    | Multi-line comment.        |

### **Packages and Imports**

| **Symbol**  | **Purpose**                              |
|-------------|------------------------------------------|
| `package`   | Declares the package name.               |
| `import`    | Imports packages or libraries.           |

### **Variable and Constant Declaration**

| **Symbol**  | **Purpose**                                                            |
|-------------|------------------------------------------------------------------------|
| `var`       | Declares a variable with an explicit type.                             |
| `:=`        | Declares and initializes a variable with type inference.               |
| `const`     | Declares a constant.                                                   |
| `new`       | Allocates memory for a variable and returns a pointer to it.           |
| `make`      | Allocates and initializes slices, maps, and channels.                  |
| `_`         | Blank identifier, used to ignore values.                               |

### **Data Types and Structures**

| **Symbol**  | **Purpose**                                                            |
|-------------|------------------------------------------------------------------------|
| `type`      | Defines a new type or type alias.                                      |
| `struct`    | Declares a structure, a collection of fields.                          |
| `interface` | Declares an interface, specifying a set of method signatures.          |
| `map`       | Declares a map, a collection of key-value pairs.                       |
| `chan`      | Declares a channel, used for goroutine communication.                  |

### **Function Declaration and Control**

| **Symbol**  | **Purpose**                                                                 |
|-------------|-----------------------------------------------------------------------------|
| `func`      | Declares a function.                                                        |
| `return`    | Exits a function and optionally returns a value.                            |
| `defer`     | Schedules a function to run just before the surrounding function returns.   |
| `go`        | Launches a goroutine, a lightweight thread of execution.                    |
| `...`       | Variadic function parameter, allows a function to accept variable arguments.|
| `()`        | Used in function calls, declarations, and grouping expressions.             |

### **Flow Control**

| **Symbol**    | **Purpose**                                                                 |
|---------------|-----------------------------------------------------------------------------|
| `if`          | Conditional statement.                                                      |
| `else`        | Follows an `if` to specify an alternative block of code.                    |
| `switch`      | Conditional statement that selects among multiple branches.                 |
| `case`        | A branch in a `switch` statement.                                           |
| `default`     | The default branch in a `switch` statement if no other `case` matches.      |
| `for`         | The only looping construct in Go, used for loops, iteration, and more.      |
| `range`       | Iterates over elements in arrays, slices, maps, channels, or strings.       |
| `break`       | Exits a loop or a `switch` statement.                                       |
| `continue`    | Skips the current iteration of a loop and proceeds to the next iteration.   |
| `goto`        | Transfers control to a labeled statement.                                   |
| `fallthrough` | Proceeds to the next case in a `switch` statement.                          |
| `select`      | Waits on multiple channel operations, blocking until one can proceed.       |

### **Operators**

| **Symbol**  | **Purpose**                                         |
|-------------|-----------------------------------------------------|
| `+`         | Adds numbers or concatenates strings.               |
| `-`         | Subtracts numbers.                                  |
| `*`         | Multiplies numbers.                                 |
| `/`         | Divides numbers.                                    |
| `%`         | Modulus operator, returns the remainder of division.|
| `=`         | Assigns a value to a variable.                      |
| `==`        | Checks if two values are equal.                     |
| `!=`        | Checks if two values are not equal.                 |
| `<`         | Less than comparison.                               |
| `>`         | Greater than comparison.                            |
| `<=`        | Less than or equal to comparison.                   |
| `>=`        | Greater than or equal to comparison.                |
| `&&`        | Logical AND.                                        |
| `\|\|`      | Logical OR.                                         |
| `!`         | Logical NOT.                                        |
| `<<`        | Bitwise left shift.                                 |
| `>>`        | Bitwise right shift.                                |
| `&`         | Bitwise AND.                                        |
| `\|`        | Bitwise OR.                                         |
| `^`         | Bitwise XOR.                                        |
| `&^`        | Bit clear (AND NOT).                                |
| `&`         | Address-of operator, returns the memory address.    |
| `*`         | Dereference operator, accesses the value at an address (also used for pointer declaration). |

### **Miscellaneous**

| **Symbol** | **Purpose**                                    |
|------------|------------------------------------------------|
| `.`        | Accesses a field or method of a struct or package. |
| `[]`       | Declares an array, slice, or index.               |
| `{}`       | Denotes a block of code, such as in functions, structs, and loops. |
| `:`        | Separates a label name from the statement in a `goto` or `switch` statement. |
| `,`        | Separates elements in a list, such as function parameters or struct fields. |
| `nil`      | Represents a zero value for pointers, interfaces, maps, slices, channels, and function types. |
