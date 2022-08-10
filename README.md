# misc-cpp-projs/threadpool

NOTE:  This code is not fully tested yet, and should be considered under  development code.

This project contains the C++ source code of a thread pool management design.
The initial thread pool management design was first implemented in Java 
by [Rubens](http://www.rubens-gomes.com) in 1999.  The link to that source code can 
be found below at:

[Java Thread Pool Source Code] ( https://github.com/rubensgomes/misc-java-projs/tree/master/threadpool)

## Environment

The development environment consists of Linux (or Linux-Like) environment with C++ (2011-C++11) GNU compiler, and the Boost C++ source libraries.

## Build and Run 

A Makefile is provided in each folder to build a test application.  The user should review the Makefile to ensure that its settings (like INCLUDE and LIB paths) are appropriately set for the environment.

To run a build at the Linux shell type:

    make clean; make

