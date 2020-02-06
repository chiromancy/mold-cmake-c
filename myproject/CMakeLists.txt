cmake_minimum_required(VERSION 3.3)
project(myproject)

# set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS}")

set(SOURCE_FILES main.c)

add_executable(myproject ${SOURCE_FILES})
