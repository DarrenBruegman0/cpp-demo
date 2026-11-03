cmake_minimum_required(VERSION 3.15)
project(demo)

set(SOURCES 
    src/main.cpp
    include/basic_math.cpp
)

# Define the executable target
add_executable(my_program ${SOURCES})

target_include_directories(my_program PRIVATE .)
