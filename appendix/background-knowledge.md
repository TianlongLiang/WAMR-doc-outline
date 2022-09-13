# Some background knowledge

In this section, we aggregate some basic background knowledge and jargons in the field of our project. This section could be served as a refresher for those who has left academia for a while and can't fully recall all the weary details and exact meaning of jargons in compiler course. Also, it would be a nice primer for those who didn't take such course and has interest in such field(and of course, our awesome WAMR project).

We think provide such section would be really nice so that you don't have to Google around. If there is anything you find inaccurate, you think should be included, or even better, you have something for us that you think would took this section to next level, do feel free to reach out to us on [Github](TODO:placeholder)!

Without further ado, let's dive right in our exciting recitation/learning journey!

## 1. Compiler

### 1.1 What is compiler?

Strictly speaking(formal definition you usually find in textbook), compiler is a special computer program, system program(serve as a platform for other software) to be more precise. It takes a source program as input and output a target program as result. Source program is written in source programming language and usually it's a high level programming language such as C/C++, Java, Rust and so on. Target program is written in target programming language would be a low level programing language like assembly. Take C/C++ as an example, the input for gcc compiler(component) is a C/C++ translation unit(a source file along with any header it used), the output is platform dependent assmbly code.

But in our daily life, what we normally mean when we refer to the word compiler is compiler toolchain, which comprise of a compiler, assembler and linker. Assembler is in charge of translating compiled translation unit(object file) from assembly to truly machine readable machine code and linker is used to link all the parts of the program(object files) together into one executable file. Together they are able to translate our human readable source code(potientially many files) into a program could run on machine.

For now, we will mainly focused on the more strictly definition, because personally I think the concept and algorithm compiler use more closely pertain to our WAMR project(Also, due to the limited knowledge the writer possess regards the other two parts).

TODO: graph

### 1.2 Structure and algorithm involved

TODO: graph

Since we alright know what compiler is, now let's learn more details about compiler. First, let's talk about structure of compiler and the algorithm related to each part. Normally, the compiler is consist of three parts, Front End, Optimizer and Back End:

- Front End: in some sense, this part is more "mature", the theory involved and actual implementation is more or less stable nowadays. The main purpose it serve is gathering textual information from source-language program and understand it both syntactically and semantically. After that, encoding the knowledge it has into Intermidiate Representation. The theory behind Front End are formal language theory(Scanners & Parsers) and lattice theory(Elaboriation for type checking).

- Optimizer: as the name suggests, the goal of Optimizer is to optimize the performance of our program. Clever readers may be conscious of the difficulty when they hear about the word "optimize". Indeed, the Optimizer is key part of our infrastructure, it analyse the input IR and transform it into definitive IR, normally through multiple pass, gradually accumlate knowledge of the program and apply better(hopefully) transformation to it. The output(definitive IR) is semantically equivalent to input IR so that it preserve the original meaning of the program we are compiling. The list of theory and algorithm could be used for 

- Back End: like Optimizer, the Back End has many open problems to tackle due to the complexiy nature of the probelm it tries to save

## 2. Interpreter

## 3. Runtime system

- similarity

- difference
