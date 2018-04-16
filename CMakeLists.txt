cmake_minimum_required(VERSION 3.5 FATAL_ERROR)

project(marcus LANGUAGES CXX)

set(CMAKE_POSITION_INDEPENDENT_CODE ON)

add_subdirectory(api)
add_subdirectory(modules)
add_subdirectory(example)
