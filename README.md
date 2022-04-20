"# Assignment3" 
Assignment 3A
-
A program that adds and subtracts 32-bit numbers
After installing the assembler on the computer, enter the following program,
save it, assemble it and run it. Do not forget to add a comment with your
name in it.
You will hand in a listing (e.g.,
addsum.asm
) that should include your name
TITLE Add and Subtract (AddSum.asm)
;This program adds and subtracts 32
-
bit integers
; Caterina Pentcheva
INCLUDE Irvine32.inc
.code
main
PROC
mov
eax, 10000h
; EAX = 10000h
add
eax, 40000h
; EAX = 50000h
sub
eax, 20000h
; EAX = 30000h
call
DumpRegs
; display registers
exit
main
ENDP
END
main
Assignment 3B: Adding 4 32-Bit Integer Variables
The program will contain four 32-
bit integer variables and add these values together, saving the result in a variable. The sum should still be in the EAX register when you call the library routine DumpRegs.
Have your values initialized in the data segment
