#VirtualMachine

This is the final assignment of the CS11 C Caltech lectures.

Project Description:
CS11C Assignment 8. This application implements an extremely simple virtual machine but powerful enough to do complex computations.
The virtual machine is implemented as a struct which contains the following:
1. A stack whicj can be at most 256 elements large
2. A stack poinet
3. A group of 16 registers
4. A memory region where VM instructions are stored
5. An instruction poiner which tells us where we are in the instruction array.

Instruction set:
*NOP - no operation; do nothing.
*PUSH - means to push onto the top of the stack a standard 4-byte integer.
*POP - pop the top of the stack.
*LOAD - means to load the value in register to the TOS.
*STORE - stores the TOS to register and pop the TOS.
*JMP - is use to go to a location in the instruction array.
*JZ - jump if top of stack is zero.
*JNZ - jump if top of stack is nonzero.
*ADD - pop the top two elements on the stack and replace them with their sum.
*SUB - pop the top two elements on the stack and replace them with their difference.
*MUL - pop the top two elements on the stack and replace them with their product.
*DIV - pop the top two elements on the stack and replace them with their division.
*PRINT - print the TOS and pop the TOS.
*STOP - halt the program.

