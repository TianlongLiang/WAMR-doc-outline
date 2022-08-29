# WAMR documentation outline

TODO: gitbook, host on github?

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
- main parts it provides and breif introduction of each part
  - "iwasm" VM core
  - "wamrc" AOT compiler
  - application framework
  - dynamic management

more details about background knowledge(compiler, interpreter, runtime system) are in [Appendix B](#appendix-b-some-background-knowledge)

details on how to build and use each part properly and where you may want to use it can be found in [section 3.tutorial](#3-tutorial)

## 2. Getting started

A hello world program

### 2.1 Compile and build on host

dependencies, how to build on different platform...

[more details](#3-tutorial)

### 2.2 Using docker

more example programs in [section 4. Examples](#4-examples)

## 3. Tutorial

- **how to build different parts with different mode on different platforms , and how to decide which mode to apply based on corresponding scene**
- embedding in the language you prefer
  - C/C++
  - Python
  - Go
- debuging
- benchmark demonstrate performance difference when it comes to use different mode

## 4. Examples

TODO: samples with some more details/docker maybe?

demonstrate different features

## 5. User case

TODO: details?

## 6. Contributing to WAMR

- **Architecture**
- on coming features
- how/what to contribute
- code styles/guideline

## Appendix A WebAssembly details

webassembly in action

## Appendix B Some background knowledge

- compiler
- interpreter
  - JIT
- runtime system
