C++ wrapper for Mongoose http server
------------------------------------
C++ wrapper author: Piotr Likus
Version: 1.2

This code repository contains C++ wrapper for mongoose http server library.

Original http server code & it's documentation is stored in directory:
  ../mongoose

Wrapper project home:
  https://github.com/vpiotr/mongoose_cpp
    
Files and directories:
------------------------
\include     - include files
\src         - source code files 

Example of C++ web server 
---------------------------
\src\test\mongotest.cpp

To run it on Windows:
- compile library project "mongoose" - in \build directory
- compile program project "mongotest" - in \build directory
- execute "\bin\runme.cmd" script
- open in your browser address "http://127.0.0.1:8080/info"

Tested compilers:
-----------------
- VS2010 Express SP1
- Code::Blocks 10.05 + MinGW + gcc 4.5

Final notes
---------------------------
For original Mongoose project information please read 
  ..\mongoose\readme.md
 

