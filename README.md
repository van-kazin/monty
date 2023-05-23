0x19. C - Stacks, Queues - LIFO, FIFO
=====================================

-   By Peter Van Kazin Ayittah (@van-kazin)



## Allowable opcodes and what they do;
| opcode | functionality |
| --- | --- |
| push	| add element to the 'top' of stack and 'end' of queue. |
| pop	| remove element from 'top' of stack and 'end' of queue. |
| pall	| print every member of the structure. |
| pint	| prints the member value at the top of stack. |
| swap	| swaps the order of the 1st and 2nd elements in stack. |
| add	| add top two member values. |
| sub	| subtract the top element from the 2nd top element. |
| div	| divide the 2nd element by the top element. |
| mul	| multiply the top two elements of the stack. |
| mod	| the remainder when the 2nd element is divided by the top element. |
| comment	| there is the ability to parse comments found in bytecode ->'#'. | 
| pchar	| print character at the top of the stack. |
| pstr	| print the character at the top of the stack. | 
| rotl	| moves element at the top to the bottom of the stack. |
| rotr	| the bottom of the stack becomes the top. |
| queue, stack	| toggles the doubly link list implementation style. |
| nop	| opcode should do nothing. |

## Tasks

### 0. push, pall
-   SimpleImplement the push and pall opcodes.
-   The push opcode
-   The opcode push pushes an element to the stack.

### 1. pint
-  Implement the pint opcode.
-   The pint opcode
-   The opcode pint prints the value at the top of the stack, followed by a new line.

### 2. pop
-   Implement the pop opcode.
-   The pop opcode
-   The opcode pop removes the top element of the stack

### 3. swap
-   Implement the swap opcode.
-   The swap opcode
-   The opcode swap swaps the top two elements of the stack.

### 4. add
-   SimpleImplement the add opcode.
-   The add opcode
-   The opcode add adds the top two elements of the stack.

### 5. nop
-   Implement the nop opcode.
-   The nop opcode
-   The opcode nop doesn’t do anything.

### 6. sub
-   Implement the sub opcode.
-   The sub opcode
-   The opcode sub subtracts the top element of the stack from the second top element of the stack.

### 7. div
-   Implement the div opcode.
-   The div opcode
-   The opcode div divides the second top element of the stack by the top element of the stack.

### 8. mul
-   Implement the mul opcode.
-   The mul opcode
-   The opcode mul multiplies the second top element of the stack with the top element of the stack.

### 9. mod
-   Implement the mod opcode.
-   The mod opcode
-   The opcode mod computes the rest of the division of the second top element of the stack by the top element of the stack.

### 10. comments
-   ImplementEvery good language comes with the capability of commenting. When the first non-space character of a line is #, treat this line as a comment (don’t do anything).

### 11. pchar
-   Implement the pchar opcode.
-   The pchar opcode
-   The opcode pchar prints the char at the top of the stack, followed by a new line.

### 12. pstr #advanced
-   TheImplement the pstr opcode.
-   The pstr opcode
-   The opcode pstr prints the string starting at the top of the stack, followed by a new line.

### 13. rotl #advanced
-   TheImplement the rotl opcode.
-   The rotl opcode
-   The opcode rotl rotates the stack to the top.

### 14. rotr #advanced
-   Implement the rotr opcode.
-   The rotr opcode
-   The opcode rotr rotates the stack to the bottom.
