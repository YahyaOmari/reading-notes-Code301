# The Call Stack

## What is a call stack ..
- A call stack is a mechanism for an interpreter to keep track of its place in a script that calls multiple functions — what function is currently being run and what functions are called from within that function.

## How does call stack work ..
- Since the call Stack is organized as a stack, the caller pushes the return address onto the stack, and the called subroutine, when it finishes, pulls or pops the return address off the call stack and transfers control to that address.

## What is JavaScript maximum call stack size?
 - 65536