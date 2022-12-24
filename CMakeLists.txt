cmake_minimum_required(VERSION 3.20.0)
project(#{PROJECT_NAME})
set(CMAKE_CXX_STANDARD 20)

# source files
set(SOURCES src/main.cpp)

# executable
add_executable(#{PROJECT_NAME} ${SOURCES})
