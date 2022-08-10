# Justification for this project

NOTE:  This code is not fully tested yet, and should be considered under  development code.

This project contains the C++ source code of a thread pool management design.
I mainly wrote this project as a fun learning experience in an attempt to
map a previous version of same design written in Java a few years back.

[Java Thread Pool Source Code] (https://github.com/rubensgomes/misc-java-projs/tree/master/threadpool)

## Environment

The development environment consists of Linux (or Linux-Like) environment with C++ (2011-C++11) GNU compiler, and the Boost C++ source libraries.

## Build and Run 

A Makefile is provided in each folder to build a test application.  The user should review the Makefile to ensure that its settings (like INCLUDE and LIB paths) are appropriately set for the environment.

To run a build at the Linux shell type:

    make clean; make

