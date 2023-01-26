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
instructions. After you complete a section, run your program and ensure
everything compiles and prints out properly.

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

You may run your program as much as you want when declaring and initializing
variables within this section. You may also run the program with the debugger to
see the variables in the Java Visualizer.

Run your program after you have finished declaring and initializing all
variables in this section.

### Combine Strings Section

In this section, you will practice using the `+` operator to concatenate
multiple `String` values.

- Declare and initialize a `String` variable called `thanksName` to combine the
  strings `thanks` and `name` together.
- Print out the variable `thanksName` to the console using
  `System.out.println()`.
- The program should print `Thank you for visiting, Eric` when it executes the
  print line.

Run your program after you have finished this section to confirm the output is
what you expect.

### Arithmetic Operators Section

In this section, you will practice using various arithmetic operators on `int`
data types.

- Initialize `x` to the sum of `y` and `z`.
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

You may run your program as much as you want within this section. You may also
run the program with the debugger to see the variables in the Java Visualizer.

Run your program after you have finished this section to confirm the output is
what you expect.

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

You may run your program as much as you want within this section. You may also
run the program with the debugger to see the variables in the Java Visualizer.

Run your program after you have finished this section to confirm the output is
what you expect.

### Compound Assignment Operators Section

In this section, you will practice using some compound assignment operators with
`int` data types.

- Re-assign `x` to the value of 4.
- Use the addition compound assignment operator to re-assign `x` with the value
  of `y` added to `x`.
- Print out the variable `x` to the console using `System.out.println()`.
- Use the decrement operator to re-assign `x` to decrease its value by 1.
- Print out the variable `x` to the console.
- Use the multiplication compound assignment operator to re-assign `x` with the
  value of `x` times `z`.
- Print out the variable `x` to the console.
- In this section alone, the program should print:

```text
6
5
40
```

You may run your program as much as you want within this section. You may also
run the program with the debugger to see the variables in the Java Visualizer.

Run your program after you have finished this section to confirm the output is
what you expect.

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
