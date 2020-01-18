cmake_minimum_required(VERSION 2.8)

project(MYPROJECT)
set(CMAKE_BUILD_TYPE Debug)
enable_testing()
add_subdirectory(myproject)
add_subdirectory(test)
