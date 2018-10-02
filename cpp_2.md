# ADVANCED PROGRAMMING

## Naming Conventions

Extensions:

`.cc
.cpp
.CC
.cxx`

`.h
.hpp`


Compilers:
`g++`

Shortest program:

`int main(){}`

If you don't write anything inside the main, it returns 0 by default.
It's equivalent to:

`int main(){ return 0; }`

Compile:

`g++ hello.cc -o hello.x`

Run:

`./hello.x`

Get the value:

`echo $?`


## Hello, World!

`#include <iostream>

int main(){
    std::cout << "Hello, World!\n";
}`

C++ is a statically typed language.

## Compilation

`make`

Or, to make in parallel:

`make -j`



