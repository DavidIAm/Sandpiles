set(SOURCES testsandpile.cpp
            main.cpp)

add_executable(testsandpile ${SOURCES})

target_link_libraries(testsandpile libsandpile ${GTEST_LIBRARIES} ${GMOCK_LIBRARIES})

install(TARGETS testsandpile DESTINATION bin)
