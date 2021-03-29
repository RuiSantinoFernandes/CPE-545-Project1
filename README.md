# CPE-545-Project1
RTOS Timer Management- for project 1 we are tasked to design a timer management system for the Real Time Operating System that is being developed in house for use in an embedded communication device

Rui Fernandes

Compiled on Windows 10 using msys64
GCC version 6.4.0 (GCC)
C++

Timer Manager
=============

This is the Timer Manager created for the Real Time Operating System being developed in-house. 
Sample Application is provided along with code to test the Timer Manager Code.

File Structure
==============
TimerAPI.c 			-> Contains Timer Manager Public and Private functions
Application.c		-> Contains sample Application code to test the Timer Manager

TimerAPI.h			-> Header file containing Timer API declarations
TimerMgrHeader.h	-> Header file containing Timer related defines ans structures
TypeDefines.h		-> Header file describing the basic Type Defines

Platform
========
Linux with code developed in C Language

Instruction to Compile and Run
==============================
Makefile is provided which handles all the compilation and linking

run below commands in the extracted folder
-> cd TimerManager
-> make clean
-> make
-> ./TimerMgr
(You need to provide the input for the number of Timers required in the pool for the OS)
