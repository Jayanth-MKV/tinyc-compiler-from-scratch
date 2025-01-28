# TinyC-Compiler
Compiler for the TinyC language from the lexical-analysis to  target-code-generation

Every TinyC program has an optional global declarations followed by one or more functions and one function must be main.

Every TinyC function has zero or more TinyC statements

Every TinyC statement is any of the following, an assignment statement, a control flow statement, a return statement, a declaration statement, a TinyC print statement
![tc_2](https://user-images.githubusercontent.com/93820457/202493632-afda1dd4-9662-4cf2-934e-5a893ef9e296.png)

#Compilation:\
-> Lexical analysis\
-> Syntax Analysis\
-> Semantic Analysis <br />
-> Intermediate code generation\
-> Code Optimization\
-> Code generation

#Interpretation:\
-> Lexical analysis \
-> Syntax Analysis \
-> Semantic Analysis \
-> Evaluate statements

![tc_1](https://user-images.githubusercontent.com/93820457/202493598-77a76e1a-3783-48ba-98a2-f3037782dcda.png)

Intermediate code generation is an important phase in the compiler design process. It is the step that comes after the syntax analysis phase, in which the source code is parsed and the abstract syntax tree (AST) is constructed. The intermediate code generation phase takes the AST as input and generates a form of code that is easier for the compiler to work with than the original source code. This intermediate code, also known as intermediate representation (IR), is then passed on to the next phase of the compiler, which is typically code optimization and code generation.

It takes the AST as input and generates a form of code that is more suitable for the next phase of the compiler to work with. There are various forms of intermediate code, each with its own advantages and disadvantages. The example code above provides an example of an intermediate code generation system for an AST, using a three-address code approach. The choice of intermediate code representation can have a significant impact on the performance of the compiler, and it is a trade-off between the ease of generation and the efficiency of the final machine code.
