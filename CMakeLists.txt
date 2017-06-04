# Define minimum cmake version
cmake_minimum_required(VERSION 2.8.11)

# Define project name
project(mock-formula)

# Define version number
set(VERSION "0.0.1")

# Binary output dir
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR})

# Define binary target
add_executable(mock-formula main.c)

