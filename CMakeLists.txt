cmake_minimum_required(VERSION 3.10)

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_STANDARD_REQUIRED True)

project(DSA VERSION 1.0)

option(ENABLE_TESTING "Enable unit tests" OFF)

include_directories("include")
configure_file(include/config.h.in include/config.h)

add_library(DSA src/dummy.cxx)

if(ENABLE_TESTING)
    add_subdirectory(tests)
endif()
