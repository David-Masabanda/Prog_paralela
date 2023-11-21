cmake_minimum_required(VERSION 3.26)
project(Ejemplo01)

set(CMAKE_CXX_STANDARD 17)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -mavx")

add_executable(Ejemplo01 main.cpp)
