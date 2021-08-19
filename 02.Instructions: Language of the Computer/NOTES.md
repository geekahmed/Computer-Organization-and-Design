## 2.1: Introduction
 - Instruction Set is the vocabulary of commands understood by a given
   architecture.
 - Stored Program Concept is the idea that instructions and data of many types can be stored in memory as numbers, leading to the stored-program computer.
## 2.2: Operations of the Computer Hardware
 - The first design principle is "Simplicity favors regularity".
## 2.3: Operands of the Computer Hardware
 - Registers are primitives used in hardware design that are also
   visible to the programmer when the computer is completed.
 - The word is the natural unit of access in a computer, usually a group of 32 bits, corressponds to the size of a register in the MIPS architecture.
 - The second design principle is "Smaller is faster".
 - Data Transfer Instruction is a data command that moves data between memory and registers.
 - The Address is a value used to delineate the location of a specific data element within a memory array.
 - Alignment restriction is a requirement that data be aligned in memory on natural boundaries.
 - Computers divide into those that use the address of the leftmost "big end byte" as the word address VS those that use the rightmost "little end byte".
 - Spilling Registers is a process of putting less commonly used variables into memory.
 - Registers take less time to access and have higher throughput thant memory due to the hardware principle relating the size and speed.
 - Accessing registers uses less energy than accessing memory.
 -  The third design principle is "Make the common case fast".
 - The rate of increase in the number of registers in a chip is very slow over time. Since programs are usually distributed in the language of the computer, there is intertia in instruction set architecture, and so the number of registers increases only as fast as new instruction sets become viable.
## 2.4: Signed and Unsigned Numbers
## 2.5: Representing Instructions in the Computer
