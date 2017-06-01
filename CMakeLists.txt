cmake_minimum_required(VERSION 3.7)
project(NScan)

set(CMAKE_C_STANDARD 99)

set(SOURCE_FILES main.c header.h header.c)
add_executable(NScan ${SOURCE_FILES})