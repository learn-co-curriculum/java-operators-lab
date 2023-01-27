# Operators Lab

## Learning Goals

- Practice declaring and initializing variables in Java.
- Practice using different operators.

## Introduction

In this lab, you are going to practice declaring and initializing variables
while also practicing using various operators that you have learned in this
section.

Fork and clone this repository. When you do, you will see a `Lab.java` file.
This is where you will put all of your code. Note the comments in the file as
well. This should provide a basic layout of where to put certain parts of your
code.

## Instructions

Each of the comments in the `Lab.java` file will represent a section from these
instructions.

## Testing Your Code

During each section, feel free to run the program as much as you want to ensure
the output is what you expect. You may also run the program with the debugger to
see the variables in the Java Visualizer. You could also use the browser based
visualizer
[here](https://pythontutor.com/java.html#code=public%20class%20Lab%20%7B%0A%20%20%20%20public%20static%20void%20main%28String%5B%5D%20args%29%20%7B%0A%20%20%20%20%20%20%20%20//%20Variables%0A%0A%20%20%20%20%20%20%20%20//%20Combine%20Strings%20Section%0A%0A%20%20%20%20%20%20%20%20//%20Arithmetic%20Operators%20Section%0A%0A%20%20%20%20%20%20%20%20//%20Relational%20Operators%20Section%0A%0A%20%20%20%20%20%20%20%20//%20Compound%20Assignment%20Operators%20Section%0A%0A%20%20%20%20%7D%0A%7D&cumulative=false&heapPrimitives=nevernest&mode=edit&origin=opt-frontend.js&py=java&rawInputLstJSON=%5B%5D&textReferences=false)
as well.

### Variables

In this section, declare and initialize the variables you will work with in this
program.

- Declare a `boolean` variable called `result`.
- Declare an `int` variable called `x`.
- Declare and initialize an `int` variable called `y` to the value 2.
- Declare and initialize an `int` variable called `z` to the value 8.
- Declare and initialize a `String` variable called `thanks` to the value
  "Thank you for visiting, ".
- Declare and initialize a `String` variable called `name` to the value "Eric".

Run your program after you have finished declaring and initializing all
variables in this section. This section produces no output as there are no print
statements, but you should still make sure it runs and compiles without error.

### Combine Strings Section

In this section, you will practice using the `+` operator to concatenate
multiple `String` values.

- Declare and initialize a `String` variable called `thanksName` to combine the
  strings `thanks` and `name` together.
- Print out the variable `thanksName` to the console using
  `System.out.println()`.
- The program should print `Thank you for visiting, Eric` when it executes the
  print line.

### Arithmetic Operators Section

In this section, you will practice using various arithmetic operators on `int`
data types.

- Initialize `x` to the sum of `y` and `z`.
  - Remember, at this point, `x` has been declared but not initialized.
- Print out the variable `x` to the console using `System.out.println()`.
- Assign `x` to the quotient of `z` divided by `y`.
- Print out the variable `x` to the console.
- Assign `x` to the following expression:
  - Write the expression where `z` is multiplied with itself.
  - Take the product of the previous expression and mod it with `y`.
    - Hint: product % `y`.
- Print out the variable `x` to the console.
- In this section alone, the program should print:

```text
10
4
0
```

### Relational Operators Section

In this section, you will practice using relational operators with `int` data
types. Remember, the result of using relational operators is a `boolean`.

- Initialize `result` to check if `x` is less than or equal to `y`.
- Print out the variable `result` to the console using `System.out.println()`.
- Assign `result` to check if `y` is not equal to `z`.
- Print out the variable `result` to the console.
- Assign `result` to check if `z` is less than `x`
- Print out the variable `result` to the console.
- In this section alone, the program should print:

```text
true
true
false
```

### Compound Assignment Operators Section

In this section, you will practice using some compound assignment operators with
`int` data types.

- Re-assign `x` to the value of 4.
- Use the addition compound assignment operator (`+=`) to re-assign `x` with the
  value of `y` added to `x`.
- Print out the variable `x` to the console using `System.out.println()`.
- Use the decrement operator (`--`) to re-assign `x` to decrease its value
  by 1.
- Print out the variable `x` to the console.
- Use the multiplication compound assignment operator (`*=`) to re-assign `x`
  with the value of `x` times `z`.
- Print out the variable `x` to the console.
- In this section alone, the program should print:

```text
6
5
40
```

## Expected Output

The expected output of the program should be:

```text
Thank you for visiting, Eric
10
4
0
true
true
false
6
5
40
```
