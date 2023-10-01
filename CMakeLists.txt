cmake_minimum_required(VERSION 3.26)
project(Glacier C)

set(CMAKE_C_STANDARD 11)

add_executable(Glacier src/main.c
        src/common.h
        src/chunk.h
        src/chunk.c
        src/memory.h
        src/memory.c
        src/debug.h
        src/debug.c
        src/value.h
        src/value.c
        src/vm.h
        src/vm.c)
