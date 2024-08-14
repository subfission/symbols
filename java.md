# Java symbols

### **Comments**

| **Symbol** | **Purpose**                                       |
|------------|---------------------------------------------------|
| `//`       | Single-line comment.                              |
| `/* */`    | Multi-line comment.                               |
| `/** */`   | Documentation comment, used to generate Javadoc.  |

### **Variable Declaration and Assignment**

| **Symbol** | **Purpose**                                                    |
|------------|----------------------------------------------------------------|
| `=`        | Assigns a value to a variable.                                 |
| `final`    | Declares a constant or prevents method overriding/inheritance. |

### **Data Types**

| **Symbol** | **Purpose**                                          |
|------------|------------------------------------------------------|
| `int`      | Integer data type.                                   |
| `float`    | Floating-point data type.                            |
| `double`   | Double precision floating-point data type.           |
| `char`     | Character data type.                                 |
| `String`   | String data type.                                    |
| `boolean`  | Boolean data type (`true` or `false`).               |
| `byte`     | 8-bit integer data type.                             |
| `short`    | 16-bit integer data type.                            |
| `long`     | 64-bit integer data type.                            |
| `void`     | Represents no return type.                           |
| `null`     | Represents a null value or no value at all.          |

### **Control Flow**

| **Symbol**  | **Purpose**                                                                               |
|-------------|-------------------------------------------------------------------------------------------|
| `if`        | Conditional statement.                                                                    |
| `else`      | Specifies an alternative block of code if the `if` condition is not met.                  |
| `else if`   | Specifies a new condition to test if the previous `if` or `else if` condition was false.  |
| `switch`    | Selects among multiple branches based on a value.                                         |
| `case`      | A branch in a `switch` statement.                                                         |
| `default`   | The default branch in a `switch` statement if no other `case` matches.                    |
| `for`       | Loop that iterates a fixed number of times.                                               |
| `while`     | Loop that continues as long as a condition is `true`.                                     |
| `do`        | Executes a loop at least once before checking the condition.                              |
| `break`     | Exits the nearest enclosing loop or `switch` statement.                                   |
| `continue`  | Skips the rest of the current loop iteration and continues with the next iteration.       |
| `return`    | Exits a method and optionally returns a value.                                            |

### **Classes and Object-Oriented Programming**

| **Symbol**  | **Purpose**                                                                    |
|-------------|--------------------------------------------------------------------------------|
| `class`     | Declares a class.                                                              |
| `extends`   | Inherits properties and methods from a parent class.                           |
| `implements`| Implements an interface.                                                       |
| `interface` | Declares an interface, a contract that a class can implement.                  |
| `abstract`  | Declares an abstract class or method that cannot be instantiated directly.     |
| `final`     | Prevents a class from being extended, or a method from being overridden.       |
| `static`    | Declares a method or variable that belongs to the class, not instances.        |
| `this`      | Refers to the current object instance.                                         |
| `super`     | Refers to the parent class, often used to call parent constructors or methods. |
| `new`       | Creates a new instance of a class.                                             |
| `null`      | Represents no object or null value.                                            |
| `enum`      | Declares an enumerated type, a fixed set of constants.                         |

### **Methods**

| **Symbol**  | **Purpose**                                                                 |
|-------------|-----------------------------------------------------------------------------|
| `void`      | Indicates that a method does not return a value.                            |
| `return`    | Exits a method and optionally returns a value.                              |
| `static`    | Declares a method that belongs to the class, not instances.                 |
| `final`     | Prevents a method from being overridden in subclasses.                      |
| `abstract`  | Declares a method without implementation, to be defined in subclasses.      |
| `synchronized` | Ensures that a method or block is only accessed by one thread at a time. |

### **Access Modifiers**

| **Symbol**   | **Purpose**                                        |
|--------------|----------------------------------------------------|
| `public`     | Accessible from any other class.                   |
| `protected`  | Accessible within the same package and subclasses. |
| `private`    | Accessible only within the same class.             |
| `default`    | (no modifier) Accessible within the same package.  |

### **Operators**

| **Symbol**  | **Purpose**                                             |
|-------------|---------------------------------------------------------|
| `+`         | Adds numbers or concatenates strings.                   |
| `-`         | Subtracts numbers.                                      |
| `*`         | Multiplies numbers.                                     |
| `/`         | Divides numbers.                                        |
| `%`         | Modulus operator, returns the remainder of division.    |
| `++`        | Increments a value by 1.                                |
| `--`        | Decrements a value by 1.                                |
| `==`        | Checks if two values are equal.                         |
| `!=`        | Checks if two values are not equal.                     |
| `<`         | Less than comparison.                                   |
| `>`         | Greater than comparison.                                |
| `<=`        | Less than or equal to comparison.                       |
| `>=`        | Greater than or equal to comparison.                    |
| `&&`        | Logical AND.                                            |
| `\|\|`      | Logical OR.                                             |
| `!`         | Logical NOT.                                            |
| `&`         | Bitwise AND.                                            |
| `\|`        | Bitwise OR.                                             |
| `^`         | Bitwise XOR.                                            |
| `~`         | Bitwise NOT.                                            |
| `<<`        | Bitwise left shift.                                     |
| `>>`        | Bitwise right shift.                                    |
| `>>>`       | Bitwise unsigned right shift.                           |
| `=`         | Assigns a value to a variable.                          |
| `+=`        | Adds to a variable and assigns the result.              |
| `-=`        | Subtracts from a variable and assigns the result.       |
| `*=`        | Multiplies a variable and assigns the result.           |
| `/=`        | Divides a variable and assigns the result.              |
| `%=`        | Applies modulus to a variable and assigns the result.   |
| `?:`        | Ternary operator, a shorthand for `if-else` conditions. |

### **Arrays and Collections**

| **Symbol**  | **Purpose**                                                                |
|-------------|----------------------------------------------------------------------------|
| `[]`        | Declares an array or accesses an array element.                            |
| `new`       | Creates a new array.                                                       |
| `ArrayList` | A resizable array, part of the Java Collections Framework.                 |
| `HashMap`   | A map that stores key-value pairs, part of the Java Collections Framework. |
| `Set`       | A collection that contains no duplicate elements.                          |
| `List`      | An ordered collection that can contain duplicate elements.                 |
| `Map`       | An object that maps keys to values, with no duplicate keys.                |
| `Iterator`  | An object that allows traversing through a collection.                     |
| `for-each`  | A loop that iterates over elements in an array or collection.              |

### **Error Handling**

| **Symbol**  | **Purpose**                                                  |
|-------------|--------------------------------------------------------------|
| `try`       | Defines a block of code to test for exceptions.              |
| `catch`     | Catches and handles exceptions thrown in the `try` block.    |
| `finally`   | Defines a block of code that will be executed no matter what.|
| `throw`     | Throws an exception manually.                                |
| `throws`    | Declares that a method can throw an exception.               |
| `Exception` | The base class for all exceptions.                           |
| `Error`     | Represents serious errors that are usually not caught.       |

### **Input/Output (I/O)**

| **Symbol**  | **Purpose**                                                       |
|-------------|-------------------------------------------------------------------|
| `System.out.println()` | Prints a line of text to the console.                  |
| `System.in`            | Represents the standard input stream (keyboard input). |
| `File`                 | Represents a file or directory path.                   |
| `InputStream`          | Represents an input stream of bytes.                   |
| `OutputStream`         | Represents an output stream of bytes.                  |
| `BufferedReader`       | Reads text from an input stream efficiently.           |
| `PrintWriter`          | Writes formatted text to an output stream.             |

### **Threads and Concurrency**

| **Symbol**     | **Purpose**                                                                                                    |
|----------------|----------------------------------------------------------------------------------------------------------------|
| `Thread`       | Represents a thread of execution in a program.                                                                 |
| `Runnable`     | Represents a task that can be executed by a thread.                                                            |
| `synchronized` | Ensures that a method or block is only accessed by one thread at a time.                                       |
| `volatile`     | Declares a variable that may be modified by multiple threads.                                                  |
| `wait()`       | Causes the current thread to wait until another thread invokes `notify()` or `notifyAll()` on the same object. |
| `notify()`     | Wakes up a single thread that is waiting on the object's monitor.                                              |
| `notifyAll()`  | Wakes up all threads that are waiting on the object's monitor.                                                 |

### **Miscellaneous**

| **Symbol**             | **Purpose**                                                                       |
|------------------------|-----------------------------------------------------------------------------------|
| `import`               | Imports a class or package.                                                       |
| `package`              | Declares a package, a namespace for classes.                                      |
| `instanceof`           | Checks if an object is an instance of a specific class or interface.              |
| `assert`               | Tests an assumption, used for debugging.                                          |
| `System.exit()`        | Terminates the program.                                                           |
| `@Override`            | Indicates that a method overrides a method in a superclass.                       |
| `@Deprecated`          | Marks a method or class as deprecated, indicating it should no longer be used.    |
| `@SuppressWarnings`    | Instructs the compiler to suppress specific warnings.                             |
| `@FunctionalInterface` | Indicates that an interface is intended to be a functional interface.             |
| `main()`               | The entry point of a Java application.                                            |
| `Javadoc`              | Documentation tool used to generate HTML documentation from Java source code.     |
