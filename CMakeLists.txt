cmake_minimum_required(VERSION 3.0)

project(simplesum)

set(SRC_LIST simplesum.cpp)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -pedantic-errors -Wall -Wextra -Werror -gdwarf-4 -std=c++20")

add_executable(${PROJECT_NAME} ${SRC_LIST})

