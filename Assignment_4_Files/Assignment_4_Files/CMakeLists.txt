cmake_minimum_required(VERSION 3.10)
project(Assignment_4_Files C)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable(Assignment_4_Files
        bst.c
        bst.h
        compare.c
        structs.h)
