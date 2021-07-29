# minimum required cmake
cmake_minimum_required(VERSION 3.9)

# project name
project(medium_ci)

# directories for outputs
#set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/tests)

# making list
set(CMAKE_C_FLAGS "-rdynamic -fPIC -g -Wformat")

# building test programs
add_executable(test_inheritance "test_inheritance.c")
add_executable(test_inheritance_2 "test_inheritance_2.c")
