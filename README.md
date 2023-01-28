# Minim Compiler #

### Summary ###
This project is a compiler for a programming language called Minim (a subset
of C). It was a semester long project created for the course CS 536: Introduction
to Compilers at UW Madison taken in the Spring of 2022. 

### How To Use ###
Assuming the Minim file ```test.minim``` is to be compiled to the assembly file ```test.s```:
- Run commands ```make clean``` and ```make all``` to build dependent code
- Run commands ```java Main test.minim test.s```
- The compiled file ```test.s``` will be able to be run on any MIPS32 emulator (e.g. QtSpim).
To open the QtSpim GUI for executing the file, run command ```qtspim test.s```

### What I Learned ###
- Finite State Machines, Context Free Grammars, Syntax Directed Translation and their relation to compilation
- Topdown/Predictive Parsing and Code Generation for creation of executable assembly code
- Pushing/popping variables, functions, literals, etc. onto/off of stack for runtime memory management 
