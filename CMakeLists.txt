cmake_minimum_required(VERSION 3.5.2)

project(Sandpiles)

set(CMAKE_INCLUDE_CURRENT_DIR ON)

include_directories(libsandpile)
add_subdirectory(test)
add_subdirectory(main)
