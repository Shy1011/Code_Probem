# C语言Extern
#include <xxx.h> 包含的变量i是可以直接使用的  
因为include其实就相当于把代码直接复制过来的.   

# Cmake
~~~cmake

cmake_minimum_required(VERSION 3.10)

set( CMAKE_CXX_COMPILER "D:/Softwares/C_Compile/mingw64/bin/g++.exe" )  #这个是C++编译器的路径

set( CMAKE_C_COMPILER "D:/Softwares/C_Compile/mingw64/bin/gcc.exe" ) #这个是C编译器的路径

cmake_minimum_required (VERSION 2.8)

project (demo)

add_executable(main test.c extern.c)
~~~