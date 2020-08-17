# The Projects about PL and Compiler

Other Resource:

[Courses](https://github.com/shining1984/PL-Compiler-Course-Collection/blob/master/Courses.md)

[Books](https://github.com/shining1984/PL-Compiler-Course-Collection/blob/master/Books.md)

[Papers](https://github.com/shining1984/PL-Compiler-Course-Collection/blob/master/Papers.md)

[Blogs](https://github.com/shining1984/PL-Compiler-Resource/blob/master/Blogs.md)

[Conferences and Journals](https://github.com/shining1984/PL-Compiler-Resource/blob/master/Conferences_Journals.md)

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

## Tools-Java/Android

1. [Redex](https://fbredex.com/)

ReDex is an Android bytecode (dex) optimizer originally developed at Facebook. It provides a framework for reading, writing, and analyzing .dex files, and a set of optimization passes that use this framework to improve the bytecode. An APK optimized by ReDex should be smaller and faster than its source.

2. [soot](https://github.com/soot-oss/soot)

Soot is a Java optimization framework. It provides four intermediate representations for analyzing and transforming Java bytecode: Baf, Jimple, Shimple, Grimp.

3. [simple-dvm](https://github.com/jserv/simple-dvm)

This is a simplified Dalvik virtual machine implementation written from scratch used for education purpose.

4. [PitifulVM](https://github.com/jserv/pitifulvm)

A shabby implementation of Java virtual machine in C.

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