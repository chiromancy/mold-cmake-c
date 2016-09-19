add_library(Catch INTERFACE)
target_include_directories(Catch INTERFACE ./..)

add_library(MYPROJECT INTERFACE)
target_include_directories(MYPROJECT INTERFACE ./../../MYPROJECT)
link_libraries(MYPROJECT)

add_executable(testTest testTest.cpp)
target_link_libraries(testTest Catch)
