# The Projects about PL and Compiler

## Compilers

1. [LLVM](http://llvm.org/)

The LLVM Project is a collection of modular and reusable compiler and toolchain technologies. Despite its name, LLVM has little to do with traditional virtual machines. The name "LLVM" itself is not an acronym; it is the full name of the project.

2. [GCC](https://gcc.gnu.org/)

The GNU Compiler Collection includes front ends for C, C++, Objective-C, Fortran, Ada, Go, and D, as well as libraries for these languages (libstdc++,...). GCC was originally written as the compiler for the GNU operating system. The GNU system was developed to be 100% free software, free in the sense that it respects the user's freedom.

3. [OpenArkCompiler](https://gitee.com/harmonyos/OpenArkCompiler)

OpenArkCompiler是来自华为方舟编译器的开源项目。

## Runtime && VM

1. [OMR](https://github.com/eclipse/omr)

The Eclipse OMR project is a set of open source C and C++ components that can be used to build robust language runtimes that support many different hardware and operating system platforms.

## Tools-LLVM/Clang

1. [screader](https://github.com/shining1984/screader)

The screader is a soure code reading tool based the libclang. It is implemented by the C. The screader can work on the clang-10.0.0 now.

2. [llvm-tutor](https://github.com/banach-space/llvm-tutor)

llvm-tutor is a collection of self-contained reference LLVM passes. It's a tutorial that targets novice and aspiring LLVM developers.

3. [clang-tutor](https://github.com/banach-space/clang-tutor)

clang-tutor is a collection of self-contained reference Clang plugins. It's a tutorial that targets novice and aspiring Clang developers.

4. [DG](https://github.com/mchalupa/dg)

DG is a library containing various bits for program analysis. However, the main motivation of this library is program slicing. The library contains implementation of a pointer analysis, data dependence analysis, control dependence analysis, and an analysis of relations between values in LLVM bitcode. All of the analyses target LLVM bitcode, but most of them are written in a generic way, so they are not dependent on LLVM in particular.

5. [Bear](https://github.com/rizsotto/Bear)

Bear is a tool that generates a compilation database for clang tooling.

6. [compiledb](https://github.com/nickdiego/compiledb)

Tool for generating Clang's JSON Compilation Database file for GNU make-based build systems.

7. [phasar](https://github.com/secure-software-engineering/phasar)

Phasar is a LLVM-based static analysis framework written in C++. It allows users to specify arbitrary data-flow problems which are then solved in a fully-automated manner on the specified LLVM IR target code. Computing points-to information, call-graph(s), etc. is done by the framework, thus you can focus on what matters.

8. [SVF](https://github.com/SVF-tools/SVF)

SVF is a source code analysis tool that enables interprocedural dependence analysis for LLVM-based languages. SVF is able to perform pointer alias analysis, memory SSA form construction, value-flow tracking for program variables and memory error checking.

## Tools-Java/Android

1. [Redex](https://fbredex.com/)

ReDex is an Android bytecode (dex) optimizer originally developed at Facebook. It provides a framework for reading, writing, and analyzing .dex files, and a set of optimization passes that use this framework to improve the bytecode. An APK optimized by ReDex should be smaller and faster than its source.

2. [soot](https://github.com/soot-oss/soot)

Soot is a Java optimization framework. It provides four intermediate representations for analyzing and transforming Java bytecode: Baf, Jimple, Shimple, Grimp.

3. [simple-dvm](https://github.com/jserv/simple-dvm)

This is a simplified Dalvik virtual machine implementation written from scratch used for education purpose.

4. [PitifulVM](https://github.com/jserv/pitifulvm)

A shabby implementation of Java virtual machine in C.

5. [Doop](http://doop.program-analysis.org/)

Doop is a framework for pointer, or points-to, analysis of Java programs. Doop implements a range of algorithms, including context insensitive, call-site sensitive, and object-sensitive analyses, all specified modularly as variations on a common code base.

## Tools-RISC-V

1. [Ripes](https://github.com/mortbopet/Ripes)

Ripes is a visual computer architecture simulator and assembly code editor built for the RISC-V instruction set architecture.

2. [RISC-V RV32I[MA] emulator with ELF support](https://github.com/sysprog21/rv32emu)

This is a RISC-V emulator for the RV32I architecture, based on TinyEMU and stripped down for RV32I only.

## Tools-Others

1. [pyright](https://github.com/microsoft/pyright)

Pyright is a fast type checker meant for large Python source bases. It can run in a “watch” mode and performs fast incremental updates when files are modified.

2. [Interpreter, Compiler, JIT](https://github.com/jserv/jit-construct)

This repository contains the programs used in Nick Desaulniers' blog post; an interpreter, a compiler, and a Just In Time (JIT) compiler for the brainfuck language. It is meant to show how similar these techniques are, and then improved by several students who learnt system programming to bring X86/ARM backend along with DynASM support.

3. [PMD](https://github.com/pmd/pmd)

PMD is a source code analyzer. It finds common programming flaws like unused variables, empty catch blocks, unnecessary object creation, and so forth. It supports Java, JavaScript, Salesforce.com Apex and Visualforce, Modelica, PLSQL, Apache Velocity, XML, XSL, Scala.

## Tutorial Projects

1. [My First Language Frontend with LLVM Tutorial](https://llvm.org/docs/tutorial/MyFirstLanguageFrontend/index.html)

2. [shecc](https://github.com/jserv/shecc)

shecc is built from scratch, targeted at 32-bit Arm architecture, as a self-compiling compiler for a subset of the C language.