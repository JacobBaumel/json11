cmake_minimum_required(VERSION 3.27)
project(json11)

set(CMAKE_CXX_STANDARD 11)

add_library(json11 STATIC json11.cpp)

target_include_directories(json11 PUBLIC include)