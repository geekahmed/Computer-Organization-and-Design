## 2.1: Introduction
 1. Instruction Set is the vocabulary of commands understood by a given
   architecture.
 2. Stored Program Concept is the idea that instructions and data of many types can be stored in memory as numbers, leading to the stored-program computer.
## 2.2: Operations of the Computer Hardware
 3. The first design principle is "Simplicity favors regularity".
## 2.3: Operands of the Computer Hardware
 4. Registers are primitives used in hardware design that are also
   visible to the programmer when the computer is completed.
 5. The word is the natural unit of access in a computer, usually a group of 32 bits, corressponds to the size of a register in the MIPS architecture.
 6. The second design principle is "Smaller is faster".
 7. Data Transfer Instruction is a data command that moves data between memory and registers.
 8. The Address is a value used to delineate the location of a specific data element within a memory array.
 9. Alignment restriction is a requirement that data be aligned in memory on natural boundaries.
 10. Computers divide into those that use the address of the leftmost "big end byte" as the word address VS those that use the rightmost "little end byte".
 11. Spilling Registers is a process of putting less commonly used variables into memory.
 12. Registers take less time to access and have higher throughput thant memory due to the hardware principle relating the size and speed.
 13. Accessing registers uses less energy than accessing memory.
 14.  The third design principle is "Make the common case fast".
 15. The rate of increase in the number of registers in a chip is very slow over time. Since programs are usually distributed in the language of the computer, there is intertia in instruction set architecture, and so the number of registers increases only as fast as new instruction sets become viable.
## 2.4: Signed and Unsigned Numbers
 16. Numbers are kept in computer hardware as a series of high and low
     electronic signals, and so they are considered base 2 numbers.
 17. Binary digit is one of the two numbers in base 2, 0 or 1, that are
     the components of information.
 18. Least significant bit is the rightmost bit in a MIPS word.
 19. Most significant bit is the leftmost bit in a MIPS word.
 20. Overflow is said to have occured, if the number that is the proper
     result of such operations cannot be represented by these rightmost
     hardware bits.
 21. Two's complement does have one negative number, -2147483648, that  has no corresponding positive number.

## 2.5: Representing Instructions in the Computer
