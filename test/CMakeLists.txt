enable_testing()

add_subdirectory(tests)

find_package(Criterion REQUIRED)
MESSAGE("Criterion Found: ${CRITERION_FOUND}")
MESSAGE("Criterion Include Dir: ${CRITERION_INCLUDE_DIR}")
add_test(NAME testTest COMMAND testTest)
