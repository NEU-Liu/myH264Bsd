cmake_minimum_required(VERSION 3.10)
project(MyH264BSD C)

set(CMAKE_C_STANDARD 99)

include_directories(src)
aux_source_directory(src TEST)

add_executable(MyH264BSD main.c ${TEST})

#add_executable(MyH264BSD main.c)