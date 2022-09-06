cmake_minimum_required(VERSION 3.13)

project(wasmgrad)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_subdirectory(3rdparty)

add_library(wasmgrad INTERFACE)
target_include_directories(wasmgrad INTERFACE cpp)

add_subdirectory(examples)
add_subdirectory(tests)
# add_subdirectory(python)
