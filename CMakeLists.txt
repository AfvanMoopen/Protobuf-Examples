# Minimum CMake required
cmake_minimum_required(VERSION 3.14.4)

# Project
project(PROTOBUF_Examples VERSION 0.0.1 LANGUAGES CXX)
set(CMAKE_CXX_STANDARD 14)
set(CMAKE_BUILD_TYPE RelWithDebInfo)


set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/bin)

add_subdirectory(protos)
add_subdirectory(examples)
