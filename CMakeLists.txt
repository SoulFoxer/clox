cmake_minimum_required(VERSION 3.23.2)
project(clox C)

set(CMAKE_C_STANDARD 23)

add_executable(clox src/main.c src/chunk.c src/memory.c header/debug.h src/debug.c header/value.h src/value.c header/vm.h src/vm.c header/compiler.h src/compiler.c header/scanner.h src/scanner.c)
