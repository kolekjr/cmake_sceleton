cmake_minimum_required(VERSION 3.10)

project(proj)

set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_STANDARD_REQUIRED True)

file(GLOB_RECURSE LOX_SOURCES "src/*.cpp")
file(GLOB_RECURSE LOX_HEADERS "include/*.h")

add_executable(proj src/main.cpp)
