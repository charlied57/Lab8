cmake_minimum_required(VERSION 3.12)
project(Lab8)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(Lab8
        BinaryTree.h
        BinaryTreeDriver.cpp
        Lab8.BinaryTrees.pdf
        RandomUtilities.h
        README.md)
