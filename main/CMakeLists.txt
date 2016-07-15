set(SOURCES main.cpp)

add_executable(Sandpile_exe ${SOURCES})

include_directories(${source_dir})

target_link_libraries(Sandpile_exe libsandpile)
