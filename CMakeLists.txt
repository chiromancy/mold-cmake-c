cmake_minimum_required(VERSION 2.8)
set(CMAKE_MODULE_PATH ${CMAKE_MODULE_PATH} "${CMAKE_SOURCE_DIR}/cmake/modules/")

project(MYPROJECT)
set(CMAKE_BUILD_TYPE Debug)
enable_testing()
add_subdirectory(myproject)
add_subdirectory(test)
