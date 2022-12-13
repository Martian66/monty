## C - Stacks, Queues - LIFO, FIFO

This project covers the implementation of the LIFO and FIFO rules for Stacks and Queues in the C programmming language.
The C scripting language, called Monty, is used to carry out these tasks.


![This is an image](https://pbs.twimg.com/media/CFYYWy6UEAE9Ow-.png)

## Description: Monty Interpreter
Monty 0.98 is a scripting language that is first compiled into Monty byte codes (Just like Python). It relies on a unique stack, with specific instructions to manipulate it.

## Monty byte code files
Files containing Monty byte codes usually have the .m extension. Most of the industry uses this standard but it is not required by the specification of the language. There is not more than one instruction per line. There can be any number of spaces before or after the opcode and its argument.


## General Requirements
* Allowed editors: vi, vim, emacs
* All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=c89
* All your files should end with a new line
* A README.md file, at the root of the folder of the project is mandatory
* Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl
* You allowed to use a maximum of one global variable
* No more than 5 functions per file
* You are allowed to use the C standard library
* The prototypes of all your functions should be included in your header file called monty.h
* Don’t forget to push your header file
* All your header files should be include guarded
* You are expected to do the tasks in the order shown in the project

## Data structures used
```
/**
 * struct stack_s - doubly linked list representation of a stack (or queue)
 * @n: integer
 * @prev: points to the previous element of the stack (or queue)
 * @next: points to the next element of the stack (or queue)
 *
 * Description: doubly linked list node structure
 * for stack, queues, LIFO, FIFO
 */

typedef struct stack_s
{
       	int n;
        struct stack_s *prev;
        struct stack_s *next;

} stack_t;

```
## Compilation & Output
* All files were compiled on Ubuntu 14.04 LTS
* The code was compiled using: `gcc -Wall -Werror -Wextra -pedantic *.c -o monty` 
* Any output must be printed on `stdout`
* Any error message must be printed on `stderr`


## Styling
All files are written in accordance to Betty styling rules

## Authors
* Kim Martin
