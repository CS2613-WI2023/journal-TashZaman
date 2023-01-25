# Journal


## **Syntax & Semantics**
### Operators

Basic operations can be broken down into a few sub components: Arithmetic, Comparative, Bitwise, and Assignment.

Within the Arithmetic operations are simple addition: "+", multiplication: "*", division: "/", and subtraction: "-".

Within the Comparative operations are the usual compare: "==", greater/less than: "<" or ">", greater/less than or equal to: "<=" or ">=".

Within the Bitwise operations are AND: "&", OR: "|" and Shift: "^".

Within the Assignment operations are assign: "=", addition assign: "+=", and subtraction assign: "-=". It is important to note that all variables are considered pointers in python.

### Code Execution

Programs should always be named as a .py file so that they can be compiled and ran via the command line. 

### Variable Declaration

In python, variables do not need to be declared with a specific type as it is mutable (can change). The variable type is automatically set after a value is given to them. We can also manually set the variable with a primative data type to make it immutable (cannot change). Common primative types consist of: int, str, float, double and boolean. We also have access to abstract data types such as lists, arrays, queues, dictionaries and tuples.

### Miscellaneous

Lines of code can be commented using "#".

Python does not require semi-colons after each line of code. Instead, semi-colons are used to concatenate multiple statements into one line.

## Data Structures and Libraries

Among the data structures are the abstract data types mentioned previously.

### Lists

Lists are essentally more flexible arrays. They are capable of inserting duplicate values and are usually always ordered. 

### Tuples

Tuples are variables that are capable of storing multiple values/characteristics. They are also immutable (cannot change).

### Dictionary

Dictionaries are a list that are capable of storing key:value pairs. A value can be obtained in a dictionary given the correct key.

### Libraries

Libraries are modules that can be imported into a project which are capable of providing additional functionality. There are various libraries that are specialized in certain areas of study such as: pandas, numpy and matplotlib which are primarily used in data science.

## Supported Paradigms

### Object-Oriented

Python is capable of object-oriented programing with its support of encapsulation and inheritance. It is quite efficent at method abstraction. Unfortunately, object-oriented code is difficult to write (at least for me) and has a slow compile time depending on the code's complexity.

### Functional

Python is quite widely used for its functional capabilites. The syntax is very easy to read and debug while the language itself is well efficient in recursion. Unfortunately functional programming can be quite memory intensive depending on the number of functions being used.

### Procedural

As python is capable of functional programming, it can also be used for procdural programming. The advantage of this is that it allows for code reusability with its implementation of generic procedures. Despite this, procedural programming can often lead to bottlenecks as the functions may become overused.
