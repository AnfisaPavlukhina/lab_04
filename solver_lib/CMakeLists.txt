cmake_minimum_required(VERSION 3.4)
project(solver)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
add_library(solver STATIC ${CMAKE_CURRENT_SOURCE_DIR}/solver.cpp)
include_directories(${CMAKE_CURRENT_SOURCE_DIR})
