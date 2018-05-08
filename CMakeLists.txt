cmake_minimum_required(VERSION 3.10)
project(functionsLib)

set(CMAKE_CXX_STANDARD 11)

add_library(functionsLib SHARED library.cpp library.h)