# 🧾 DSL Compiler in C (Lexer + Parser + IR Generator)

## 📌 Overview
This project is a simple **Domain Specific Language (DSL) Compiler** implemented in **C language**.  
It demonstrates the fundamental phases of a compiler:

- Lexical Analysis (Tokenization)
- Syntax Analysis (Simple Parsing / AST generation)
- Intermediate Representation (IR generation)

The compiler processes simple DSL statements like:

```c
let x = 5;
let y = x + 3;
