# Postfix and Prefix Evaluation

This C program demonstrates the evaluation of postfix and prefix expressions using a stack data structure.

## Description

The program includes functions to evaluate both postfix and prefix expressions. It utilizes a stack for operand storage and arithmetic operations.

## Files

- `postfix_prefix_evaluation.c`: The main source code file containing the implementation of postfix and prefix evaluation.

## How to Use

1. Clone the repository: `git clone https://github.com/your-username/postfix-prefix-evaluation.git`
2. Compile the code: `gcc postfix_prefix_evaluation.c -o postfix_prefix_evaluation`
3. Run the executable: `./postfix_prefix_evaluation`
4. The program currently has a sample postfix expression (`"a*b"`) in the `main` function. Modify the expression or replace it with your own expression for testing.

## Functions

### `evaluatePostfix(char* exp)`

This function evaluates a postfix expression and returns the result.

### `evaluatePrefix(char* exp)`

This function evaluates a prefix expression and returns the result.

### Stack Operations

- `createStack(unsigned capacity)`: Creates a stack with a given capacity.
- `isEmpty(struct Stack* stack)`: Checks if the stack is empty.
- `peek(struct Stack* stack)`: Returns the top element of the stack without popping.
- `pop(struct Stack* stack)`: Removes and returns the top element from the stack.
- `push(struct Stack* stack, char op)`: Pushes an operand or result onto the stack.

## Example

```c
char exp[] = "a*b";
printf ("Postfix evaluation: %d\n", evaluatePostfix(exp));
printf ("Prefix evaluation: %d", evaluatePrefix(exp));
```



