cmake_minimum_required(VERSION 3.3)
project(myproject)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES dummy.cpp)

add_library(myproject ${SOURCE_FILES})
