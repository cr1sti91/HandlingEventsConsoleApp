cmake_minimum_required(VERSION 3.16)

project(HandlingEvents)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED 20)

file(GLOB_RECURSE SRC_FILES src/*.cpp)
add_executable(HandlingEvents main.cpp ${SRC_FILES})
target_include_directories(HandlingEvents PRIVATE ${CMAKE_CURRENT_SOURCE_DIR}/include)