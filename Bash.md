### **Comments**

| **Symbol** | **Purpose**                |
|------------|----------------------------|
| `#`        | Single-line comment.       |

### **Variables**

| **Symbol** | **Purpose**                                                |
|------------|------------------------------------------------------------|
| `$VAR`     | Accesses the value of a variable `VAR`.                    |
| `VAR=value`| Assigns a value to a variable.                             |
| `${VAR}`   | Variable substitution with braces (for clarity).           |
| `export VAR=value` | Exports a variable, making it available to child processes. |
| `unset VAR`| Unsets a variable, removing its value.                     |
| `$#`       | Number of positional parameters (arguments).               |
| `$@`       | All positional parameters as separate strings.             |
| `$*`       | All positional parameters as a single string.              |
| `$0`       | The name of the script.                                    |
| `$1, $2, ...` | Positional arguments to the script.                     |
| `$?`       | Exit status of the last command.                           |
| `$$`       | The process ID of the current shell.                       |
| `$!`       | Process ID of the last background process.                 |

### **Control Flow**

| **Symbol**  | **Purpose**                                               |
|-------------|-----------------------------------------------------------|
| `if [ condition ]; then ... fi` | Conditional statement.                 |
| `else`      | Specifies an alternative block if the `if` condition fails.|
| `elif`      | Specifies a new condition if the previous `if` or `elif` was false. |
| `case`      | Multi-branch conditional statement.                        |
| `esac`      | Ends a `case` statement.                                   |
| `for var in list; do ... done` | Loops through a list of values.         |
| `while [ condition ]; do ... done` | Loops while the condition is true.  |
| `until [ condition ]; do ... done` | Loops until the condition becomes true. |
| `break`     | Exits a loop.                                              |
| `continue`  | Skips the current iteration of a loop and continues with the next.|
| `return`    | Exits a function and optionally returns a value.           |
| `exit`      | Exits the shell or script with a status code.              |

### **Functions**

| **Symbol**      | **Purpose**                                          |
|-----------------|------------------------------------------------------|
| `function name { ... }` | Declares a function.                         |
| `name() { ... }`        | Alternate function declaration syntax.       |
| `$1, $2, ...`           | Positional arguments within a function.      |
| `return`                | Exits a function and optionally returns a value. |

### **Operators**

| **Symbol**  | **Purpose**                                               |
|-------------|-----------------------------------------------------------|
| `=`         | Assigns a value to a variable.                            |
| `==`        | String equality comparison (inside `[[ ... ]]`).          |
| `!=`        | String inequality comparison (inside `[[ ... ]]`).        |
| `-eq`       | Integer equality comparison.                              |
| `-ne`       | Integer inequality comparison.                            |
| `-lt`       | Less than comparison.                                     |
| `-le`       | Less than or equal comparison.                            |
| `-gt`       | Greater than comparison.                                  |
| `-ge`       | Greater than or equal comparison.                         |
| `&&`        | Logical AND (inside `[[ ... ]]`).                         |
| `||`        | Logical OR (inside `[[ ... ]]`).                          |
| `!`         | Logical NOT.                                              |
| `>`         | Redirects standard output to a file (overwriting).        |
| `>>`        | Redirects standard output to a file (appending).          |
| `<`         | Redirects input from a file.                              |
| `2>`        | Redirects standard error to a file.                       |
| `&>`        | Redirects both standard output and standard error to a file. |
| `|`         | Pipes the output of one command to another command.       |

### **File Tests**

| **Symbol**  | **Purpose**                                               |
|-------------|-----------------------------------------------------------|
| `-f`        | Checks if a file exists and is a regular file.            |
| `-d`        | Checks if a directory exists.                             |
| `-e`        | Checks if a file or directory exists.                     |
| `-r`        | Checks if a file is readable.                             |
| `-w`        | Checks if a file is writable.                             |
| `-x`        | Checks if a file is executable.                           |
| `-s`        | Checks if a file is not empty.                            |
| `-L`        | Checks if a file is a symbolic link.                      |

### **String Tests**

| **Symbol**  | **Purpose**                                               |
|-------------|-----------------------------------------------------------|
| `-z`        | Checks if a string is empty.                              |
| `-n`        | Checks if a string is not empty.                          |
| `[[ str1 == str2 ]]` | Checks if two strings are equal.                 |
| `[[ str1 != str2 ]]` | Checks if two strings are not equal.             |

### **Arithmetic**

| **Symbol**  | **Purpose**                                               |
|-------------|-----------------------------------------------------------|
| `$(( expression ))` | Evaluates an arithmetic expression.               |
| `+`         | Addition.                                                 |
| `-`         | Subtraction.                                              |
| `*`         | Multiplication.                                           |
| `/`         | Division.                                                 |
| `%`         | Modulus (remainder of division).                          |
| `++`        | Increment by 1.                                           |
| `--`        | Decrement by 1.                                           |

### **Arrays**

| **Symbol**   | **Purpose**                                              |
|--------------|----------------------------------------------------------|
| `array=(elem1 elem2 elem3)` | Declares an indexed array.                |
| `${array[index]}` | Accesses an element of the array.                   |
| `${array[@]}` | Accesses all elements of the array.                     |
| `${#array[@]}` | Gets the number of elements in the array.              |
| `unset array[index]` | Removes an element from the array.               |

### **Redirection and Piping**

| **Symbol**  | **Purpose**                                               |
|-------------|-----------------------------------------------------------|
| `>`         | Redirects standard output to a file (overwriting).        |
| `>>`        | Redirects standard output to a file (appending).          |
| `<`         | Redirects input from a file.                              |
| `2>`        | Redirects standard error to a file.                       |
| `&>`        | Redirects both standard output and standard error to a file. |
| `|`         | Pipes the output of one command to another command.       |
| `< <(cmd)`  | Substitution for piping the result of a command as input. |

### **Substitution**

| **Symbol**  | **Purpose**                                               |
|-------------|-----------------------------------------------------------|
| `$(command)` | Command substitution; runs a command and returns its output. |
| `` `command` `` | Alternate command substitution syntax.               |
| `${var}`    | Variable substitution.                                    |
| `${var:-default}` | Uses `default` if `var` is unset or null.           |
| `${var:=default}` | Sets `var` to `default` if `var` is unset or null.  |
| `${var:+alternate}` | Uses `alternate` if `var` is set.                 |
| `${var:?error}` | Throws an error if `var` is unset or null.            |

### **Process Management**

| **Symbol**  | **Purpose**                                               |
|-------------|-----------------------------------------------------------|
| `&`         | Runs a command in the background.                         |
| `jobs`      | Lists background jobs.                                    |
| `fg`        | Brings a background job to the foreground.                |
| `bg`        | Continues a stopped background job.                       |
| `kill`      | Sends a signal to terminate a process.                    |
| `wait`      | Waits for background processes to finish.                 |

### **Miscellaneous**

| **Symbol**  | **Purpose**                                               |
|-------------|-----------------------------------------------------------|
| `source file` | Executes a script in the current shell.                 |
| `.`         | Equivalent to `source`, executes a script in the current shell.|
| `alias name='command'` | Creates a shortcut for a command.              |
| `unalias name` | Removes an alias.                                      |
| `trap`      | Executes a command when the shell receives a signal.      |
| `exec`      | Replaces the current shell with a specified command.      |
| `type`      | Displays the type of a command (e.g., alias, function, or builtin). |
| `which`     | Locates a command by searching the directories in the `PATH`. |
