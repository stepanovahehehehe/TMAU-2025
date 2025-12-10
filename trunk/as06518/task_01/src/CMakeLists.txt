cmake_minimum_required(VERSION 3.5)

project(tmau1)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(Tmau_Laba1 tmau1.cpp)

target_compile_options(Tmau_Laba1 PRIVATE -Wall)
