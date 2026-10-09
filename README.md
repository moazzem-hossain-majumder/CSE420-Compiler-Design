# 🛠️ CSE 420: Compiler Design

Welcome to the comprehensive study and reading materials repository for **CSE 420: Compiler Design**.

This repository contains lecture-by-lecture reading materials, theoretical breakdowns, architectural diagrams, mathematical models, worked problems, and exam review notes covering the principles and construction of modern compilers.

---

## 📚 Course Reference Materials

- **Primary Textbook:** *Compilers: Principles, Techniques, and Tools* (2nd Edition / "The Dragon Book") by Alfred V. Aho, Monica S. Lam, Ravi Sethi, and Jeffrey D. Ullman.
- **Lecture Notes:** Dr. Muhammad Nur Yanhaona (Department of Computer Science & Engineering).
- **Supplemental Articles & Guides:** Rakia Ben Sassi (*Compiler vs. Interpreter: Know The Difference*).

---

## 📑 Lecture Directory

| Lecture | Topic | Status | Reading Material |
|:---:|:---|:---:|:---:|
| **01** | **Introduction to Compilers & Language Translation**<br>*(Language Processors, Compiler vs Interpreter, Hybrid Compilation, Language-Processing System, 6 Compiler Phases, Symbol Table, Passes, Evolution, Architecture Optimizations, Static vs Dynamic)* | ✅ Completed | [Lecture 1 Notes](./Lecture%201/README.md) |
| **02** | **Lexical Analysis, Input Buffering & Regular Expressions**<br>*(Role of Lexical Analyzer, Tokens, Patterns, Lexemes, Attributes, Input Buffering, Sentinels, Formal Language Theory, Regular Expressions, Regular Definitions, Lex/Flex, Quantifiers & Lookarounds)* | ✅ Completed | [Lecture 2 Notes](./Lecture%202/README.md) |
| **03** | Syntax Analysis: Context-Free Grammars & Top-Down Parsing (LL(1)) | ⏳ Upcoming | — |
| **04** | Syntax Analysis: Bottom-Up Parsing (LR, SLR, LALR, CLR, Yacc/Bison) | ⏳ Upcoming | — |
| **05** | Semantic Analysis & Syntax-Directed Translation (SDT / SDD) | ⏳ Upcoming | — |
| **06** | Type Systems, Type Checking & Runtime Storage Environments | ⏳ Upcoming | — |
| **07** | Intermediate Code Generation (Three-Address Code, Quadruples, Triples) | ⏳ Upcoming | — |
| **08** | Machine-Independent Code Optimization (Constant Folding, Dead Code, Loops) | ⏳ Upcoming | — |
| **09** | Data-Flow Analysis & Control-Flow Graphs (CFG) | ⏳ Upcoming | — |
| **10** | Target Code Generation & Instruction Selection | ⏳ Upcoming | — |
| **11** | Register Allocation & Assignment (Graph Coloring) | ⏳ Upcoming | — |
| **12** | Runtime Storage Organization (Stack Allocation, Heap, Activation Records) | ⏳ Upcoming | — |
| **13** | Garbage Collection & Automatic Memory Management | ⏳ Upcoming | — |
| **14** | Object-Oriented Language Compilation (Dynamic Dispatch, Vtables) | ⏳ Upcoming | — |
| **15** | Just-In-Time (JIT) Compilation & Virtual Machines | ⏳ Upcoming | — |
| **16** | Compiler Optimizations for Modern Architectures (ILP, SIMD, Caches) | ⏳ Upcoming | — |
| **17** | Interprocedural Analysis & Whole-Program Optimization | ⏳ Upcoming | — |
| **18** | Static Analysis & Software Security (Taint Analysis, Bounds Checking) | ⏳ Upcoming | — |
| **19** | Domain-Specific Languages & Transpilers | ⏳ Upcoming | — |
| **20** | Advanced Topics: LLVM Infrastructure, WebAssembly & Future Trends | ⏳ Upcoming | — |

---

## 🚀 Featured Reading Modules

### 📘 [Lecture 1: Introduction to Compilers & Language Translation](./Lecture%201/README.md)
- Complete breakdown of all 6 compiler phases
- End-to-end trace of `position = initial + rate * 60`
- Solutions to Dragon Book Section 1.1 exercises & 10-language matrix
- 11 architectural diagrams, flowcharts, and exam revision cards

### 📗 [Lecture 2: Lexical Analysis, Input Buffering & Regular Expressions](./Lecture%202/README.md)
- In-depth role of Scanner, `getNextToken()`, and Symbol Table interplay
- The Core Trinity: Tokens, Patterns, and Lexemes with concrete traces
- Double-buffering scheme and the sentinel (`eof`) single-test optimization
- Formal language foundations (Alphabets, Strings, Operations on Languages)
- Regular Expressions & Regular Definitions (inductive basis, precedence, algebraic laws)
- The Lex/Flex generator ecosystem and conflict resolution rules (Longest Match & First Match)
- Comprehensive practical regex guide (Greedy vs Lazy vs Possessive, Lookarounds, Pitfalls)
- Full step-by-step solutions to Dragon Book Section 3.1 & 3.3 exercises (3.1.1–3.1.2, 3.3.1–3.3.12)
- 15 architectural diagrams, PDF screenshots, and Master Exam Revision Card

---

## 📂 Repository Structure

```
CSE420-Compiler-Design/
├── README.md               # Repository Overview & Syllabus Navigation
├── Lecture 1/
│   ├── README.md           # Master Reading Material for Lecture 1
│   ├── lecture1.md         # Companion Reading File
│   └── images/             # Architectural Diagrams & Flowcharts
├── Lecture 2/
│   ├── README.md           # Master Reading Material for Lecture 2
│   ├── lecture2.md         # Companion Reading File
│   └── images/             # Architectural Diagrams, Scans & Infographics
└── pdfs/
    ├── Lecture 1/          # Source Lecture Slides & Textbook Excerpts
    └── Lecture 2/          # Source Lecture Slides, Dragon Book Ch 3 & Regex Guide
```
