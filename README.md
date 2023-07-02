# Golang-roadmap 

## 1. Set up environment
### 1.1. Install Golang
- [Download](https://golang.org/dl/) and install Golang
- Set up environment variables
    - `GOROOT`: path to Golang installation directory
    - `GOPATH`: path to workspace directory
    - `PATH`: add `$GOROOT/bin` and `$GOPATH/bin` to `PATH`
- Check installation: `go version`

### 1.2. Install IDE
- [Download](https://www.jetbrains.com/go/download/) and install GoLand
- [Download](https://code.visualstudio.com/download) and install VSCode
- [Download](https://www.sublimetext.com/3) and install Sublime Text 3

## 2. Basic
### 2.1 Data types
- Primitive types: `bool`, `string`, `int`, `float32`, `float64`
- Aggregate types: `array`, `slice`, `map`, `struct`
- Reference types: `pointer`, `function`, `interface`, `slice`, `map`, `channel`
-[More](https://golang.org/ref/spec#Types)

### Tasks for data types
- [ ] Declare variables with primitive types
- [ ] Declare variables with aggregate types
- [ ] Declare variables with reference types

### 2.2 Variables
- Declare: `var <name> <type>`


### 2.3 Zero value
- `int`: `0`
- `float`: `0.0`
- `bool`: `false`
- `string`: `""`
- `pointer`, `function`, `interface`, `slice`, `map`, `channel`: `nil`
- `struct`: zero value of each field
- `array`: zero value of each element
- [More](https://golang.org/ref/spec#The_zero_value)

### Tasks for zero value
- [ ] Print zero value of each data type

### 2.4 Constants
- Declare: `const <name> <type> = <value>`
- [More](https://golang.org/ref/spec#Constants)


### 2.5 Operators
- Arithmetic operators: `+`, `-`, `*`, `/`, `%`, `++`, `--`
- Comparison operators: `==`, `!=`, `>`, `<`, `>=`, `<=`
- Logical operators: `&&`, `||`, `!`
- [More](https://golang.org/ref/spec#Operators)

### Tasks for operators
- [ ] Create a calculator program

### 2.6 Control flow
- `if` statement
- `switch` statement
- [More](https://gobyexample.com/if-else)

### Tasks for control flow
- [ ] Create a program to check if a number is prime or not
- [ ] Create a program to check if a year is leap year or not
- [ ] Create a program to check if a number is odd or even
- [ ] Create a program to check if a number is positive, negative or zero
- [ ] Find the maximum number in 3 numbers

### 2.7 Loop
- `for` loop
- [More](https://gobyexample.com/for)

### Tasks for loop
- [ ] Create a program to print all prime numbers from 1 to 100
- [ ] Factorial of a number
- [ ] Fibonacci sequence
- [ ] Print multiplication table of a number
- [ ] Print the Piramids with * help of loops

### 2.8 Function
- Declare: `func <name>(<params>) <return type> {<body>}`
- [More](https://gobyexample.com/functions)

### Tasks for function
- [ ] Take 2 numbers as input and return the sum
- [ ] Caculate the area of a circle with radius,trianle with 3 sides, rectangle with 2 sides
- [ ] Take a number as input and return the factorial of that number
### 2.9 Array and slice
- Declare: `var <name> [<size>] <type>`
- [More](https://gobyexample.com/arrays)

### Tasks for array and slice
- [ ] Create a program to find the maximum number in an array
- [ ] Use Built-in functions of slice and array
### 2.10 Struct
- Declare: `type <name> struct {<fields>}`
- [More](https://gobyexample.com/structs)

### 2.11 Map 
- Declare: `var <name> map[<key type>]<value type>`
- [More](https://gobyexample.com/maps)

### 2.12 Pointer
- Declare: `var <name> *<type>`
- [More](https://gobyexample.com/pointers)

### 2.13 Interface
- Declare: `type <name> interface {<methods>}`
- [More](https://gobyexample.com/interfaces)

### 2.15 Type assertion abd type switch
- Declare: `<value>.(<type>)`
- [More](https://gobyexample.com/type-assertions)

### 2.16 Error handling
- Declare: `errors.New(<message>)`
- [More](https://gobyexample.com/errors)

### 2.17 Go Modules and Packages
- [More](https://golang.org/doc/tutorial/create-module)

### 2.18 Panic, Defer and Recover
- [More](https://gobyexample.com/panic)

