`
; learn.asm
; x86-64 Assembly learning guide
;
; This file contains notes and exercise prompts only.
; It is designed for study, not execution.
; Read the sections carefully, then write your own code separately.
;
; ------------------------------------------------------------------
; 1) Assembly structure and syntax
; ------------------------------------------------------------------
;
; A typical x86-64 assembly file has sections:
;   section .data    ; initialized static data
;   section .bss     ; uninitialized data
;   section .text    ; code and executable instructions
;
; The entry point for a pure assembly Linux program is usually _start.
; Labels end with a colon and mark code or data locations.
;
; Instructions are written as:
;   mnemonic operand1, operand2
;
; Most instructions use the form dest, src.
;
; ------------------------------------------------------------------
; 2) Registers and operand sizes
; ------------------------------------------------------------------
;
; Learn the common general-purpose registers:
;   rax, rbx, rcx, rdx,
;   rsi, rdi, rbp, rsp,
;   r8..r15
;
; Each register has smaller views:
;   rax -> eax -> ax -> ah/al
;   rbx -> ebx -> bx -> bh/bl
;
; Use the correct size for the operation:
;   mov eax, 5    ; 32-bit move
;   mov rax, 5    ; 64-bit move
;
; Remember rsp is the stack pointer and rbp is often used as frame pointer.
;
; ------------------------------------------------------------------
; 3) Data movement and arithmetic
; ------------------------------------------------------------------
;
; The most common instruction is mov to copy values.
; Arithmetic examples include add, sub, imul, and xor.
;
; Understand these forms:
;   mov reg, imm      ; immediate value to register
;   mov reg, [mem]    ; load from memory
;   mov [mem], reg    ; store to memory
;   add reg, reg      ; add two registers
;   sub reg, imm      ; subtract immediate
;   imul reg, reg     ; signed multiplication
;   xor reg, reg      ; zero a register
;
; Learn how flags are set by arithmetic instructions.
;
; ------------------------------------------------------------------
; 4) Control flow and branching
; ------------------------------------------------------------------
;
; Branching uses cmp/test followed by conditional jumps.
; Common jumps:
;   je, jne, jl, jle, jg, jge
;
; Compare operands with cmp:
;   cmp rax, rbx
;
; Then choose a branch based on the flags.
;
; Unconditional jump uses jmp.
;
; Learn how to create loops:
;   label:
;       instructions
;       jmp label
;
; and conditionally exit loops with cmp/jne or cmp/jle.
;
; ------------------------------------------------------------------
; 5) Functions and calling conventions
; ------------------------------------------------------------------
;
; On Linux x86-64, function arguments are passed in:
;   rdi, rsi, rdx, rcx, r8, r9
;
; Return values are placed in rax.
;
; When defining a function, use call and ret.
; A simple function prologue can save rbp and set a new frame pointer:
;   push rbp
;   mov rbp, rsp
;
; A function epilogue restores rbp and returns:
;   pop rbp
;   ret
;
; Learn how to preserve registers that must be saved across calls.
;
; ------------------------------------------------------------------
; 6) Memory, data, and arrays
; ------------------------------------------------------------------
;
; Data labels in .data hold constants and arrays.
; Example formats:
;   msg db "hello", 0
;   values dq 1, 2, 3, 4
;
; Access memory with brackets:
;   mov rax, [values]
;   mov rax, [values + 8]   ; second qword
;
; For arrays, use an index multiplied by element size.
;
; Remember x86-64 uses little-endian byte order.
;
; ------------------------------------------------------------------
; 7) Syscalls and program exit
; ------------------------------------------------------------------
;
; Linux syscalls use syscall instruction.
; The system call number goes in rax.
; Arguments go in rdi, rsi, rdx, r10, r8, r9.
;
; Common syscalls:
;   60  : exit
;   1   : write
;   0   : read
;
; To exit cleanly, move the exit code into rdi and syscall.
;
; ------------------------------------------------------------------
; 8) Writing assembly thoughtfully
; ------------------------------------------------------------------
;
; Practice the following principles:
; - Use comments to explain what each label and block does.
; - Keep instruction sequences short and clear.
; - Name labels logically for loops and functions.
; - Check register size mismatches.
;
; Build programs by combining simple steps rather than trying to do too much at once.
;
; ------------------------------------------------------------------
; 9) Exercises to practice x86-64 assembly
; ------------------------------------------------------------------
;
; These exercises are intended for you to write your own code.
; Use the sections above as a reference but do not copy entire solutions.
;
; Exercise 1: Register arithmetic
; - Write a program that loads two values into registers.
; - Add them, subtract them, multiply them, and store the result in rax.
; - Exit with a status code based on the final value.
;
; Exercise 2: Compare and branch
; - Write a small routine that compares two registers.
; - Set a register to 1 if the first value is less than the second.
; - Otherwise set it to 0.
;
; Exercise 3: Looping with counters
; - Create a loop that sums the numbers from 1 to 10.
; - Keep the running total in one register.
; - Return the final sum in rax.
;
; Exercise 4: Function call
; - Write a function that adds two arguments.
; - Call it from _start using rdi and rsi.
; - Return the result in rax.
;
; Exercise 5: Array access
; - Define an array of 5 64-bit values in .data.
; - Write code that loops through the array and computes the total.
; - Return the total in rax.
;
; Exercise 6: String output with sys_write
; - Define a message in .data.
; - Use the write syscall to print it to stdout.
; - Exit cleanly afterward.
;
; Exercise 7: Conditional loop
; - Write a loop that counts down from 5 to 1.
; - Use cmp and conditional jumps to terminate the loop.
;
; Exercise 8: Calling convention practice
; - Write a function that computes a value from two inputs.
; - Pass values in rdi and rsi.
; - Preserve any registers you need across the call.
;
; Exercise 9: Memory indexing
; - Create an array with at least 8 values.
; - Use an index register and element size to access each item.
;
; Exercise 10: Describe your code
; - For each exercise, write comments explaining the purpose
;   of the registers and branches you use.
;
; ------------------------------------------------------------------
; 10) Learning tips
; ------------------------------------------------------------------
;
; - Assemble often and inspect object output with objdump -d.
; - Step through small programs with gdb or lldb.
; - If something does not work, simplify the code and isolate the issue.
; - Use one register per purpose when possible.
; - Practice writing code before checking a complete solution.
;
; End of x86-64 assembly learning guide.
`
