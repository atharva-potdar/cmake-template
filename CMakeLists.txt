cmake_minimum_required(VERSION 3.31)
project(tutorial)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED True)
set(CMAKE_CXX_EXTENSIONS False)

add_executable(tutorial src/main.cpp)
target_compile_options(tutorial PRIVATE -pedantic-errors -Wall -Weffc++ -Wextra -Wconversion -Wsign-conversion -Werror)
