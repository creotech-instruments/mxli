project(mxli)
cmake_minimum_required(VERSION 3.10)

set(CMAKE_C_FLAGS "-Wall -std=gnu99 -Wno-parentheses -Wno-unused-variable")

add_subdirectory(lib)
add_subdirectory(programs/mxli3)
#add_subdirectory(programs/ramloader)
#add_subdirectory(programs/ramreader)
#add_subdirectory(programs/uconsole)
