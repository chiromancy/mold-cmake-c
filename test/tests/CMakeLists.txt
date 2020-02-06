
add_library(MYPROJECT INTERFACE)
target_include_directories(MYPROJECT INTERFACE ./../../myproject)

add_executable(testTest testTest.c)
target_include_directories(testTest PUBLIC
                           ${CRITERION_INCLUDE_DIR})
target_link_libraries(testTest
                        ${CRITERION_LIBRARY})
