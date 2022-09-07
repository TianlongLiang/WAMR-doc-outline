# WAMR documentation outline

[gitbook](https://gitbook.com) eligible for Community Plan, free for open source projects

## 1. Introduction

### 1.1 WebAssembly

The basics of WebAssembly

- its origin  
- what problems does it solve  
- how does it work
- structure of its module
- what languages can be used to create module

more details about WebAssmebly can be found in [Appendix A](#appendix-a-webassembly-details)

### 1.2 WAMR project

The basics of WAMR

- what it is
- why you may want to use it
- main parts it provides and brief introduction of each part
  - "iwasm" VM core
  - "wamrc" AOT compiler
  - application framework
  - dynamic management

more details about background knowledge(compiler, interpreter, runtime system, all other jargons) are in [Appendix B](#appendix-b-some-background-knowledge)

details on how to build and use each part properly and where you may want to use it can be found in [section 3.tutorial](#3-tutorial)

## 2. Getting started

A hello world program

more example programs in [section 4. Examples](#4-unique-features-and-examples)

### 2.1 Compile and build on host

dependencies, how to build on different platform...

[more details](#3-tutorial)

### 2.2 Using docker

suppose to be easier, don't need to worry about dependencies(however, most example programs has to be checked and modified to run in current docker)

## 3. Tutorial

- **how to build different parts with different mode on different platforms , and how to decide which mode to apply based on corresponding scene**
- embedding in the language you prefer
  - C/C++
  - Python
  - Go
- benchmark demonstrate performance difference when it comes to use different mode
- debugging and IDE support

## 4. Unique features and examples

demonstrate different features with corresponding samples

TODO: add some more details maybe? fixed version of dependencies in a dockerfile so that don't need to worry about devdocker changes?

TODO: existing samples need some modification in order to run properly(tested in devdocker environment)

## 5. User case

TODO: details?

## 6. Programmer's Manual

Programmer’s Manual like [LLVM](https://llvm.org/docs/ProgrammersManual.html#introduction)?

- important APIs
- TODO: abstract Hierarchy

## 7. Community

### 7.1 Contributing to WAMR

- upcoming features
- how/what to contribute
- code styles/guideline

### 7.2 Contact us

- github
- twitter
- medium

## Appendix A WebAssembly details

Book: webassembly in action

## Appendix B Some background knowledge

- compiler
- interpreter
  - JIT
- runtime system
