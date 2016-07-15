find_package(PkgConfig)
pkg_check_modules(GTEST REQUIRED gtest>=1.7)

include_directories(${GTEST_INLCUDE_DIRS})

add_subdirectory(testsandpile)
