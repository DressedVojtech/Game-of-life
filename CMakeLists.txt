cmake_minimum_required (VERSION 3.11)

# Set the project name to your project name, my project isn't very descriptive
project ( Game-of-life CXX )

set (CMAKE_CXX_STANDARD 20)

if (NOT CMAKE_BUILD_TYPE)
    set (CMAKE_BUILD_TYPE "Release")
    message (STATUS "Build type not specified: Use Release by default")
endif (NOT CMAKE_BUILD_TYPE)

# executable
add_executable (Game-of-life main.cpp)
