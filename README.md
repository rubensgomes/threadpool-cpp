# Justification for this project

NOTE:  This code is not fully tested, and should be considered under  development code.
The source code that is provided are  mainly used for demonostrations and learning purposes only.

This project contains the C++ source code of a thread pool management design.
I mainly wrote this project as a fun learning experience sometime in 2015. This
C++ code is attempts to map a previous version of same design written in Java that
I wrote back in 1999.

[Java Thread Pool Source Code] (https://github.com/rubensgomes/threadpool-java)

## Environment

The development environment consists of Linux (or Linux-Like) environment with C++ (2011-C++11) GNU compiler, and the Boost C++ source libraries.

## Build and Run 

A Makefile is provided in each folder to build a test application.  The user should review the Makefile to ensure that its settings (like INCLUDE and LIB paths) are appropriately set for the environment.

To run a build at the Linux shell type:

    make clean; make

