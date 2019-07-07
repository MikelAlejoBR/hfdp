cmake_minimum_required(VERSION 3.7.2)

project(HFDP)

set(EXECUTABLE_OUTPUT_PATH ${CMAKE_BINARY_DIR})
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/bin)

file (GLOB SOURCES src/*.cpp)

add_executable(main ${SOURCES})
