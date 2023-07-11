cmake_minimum_required(VERSION 3.26)
project(cmake_libs)

set(CMAKE_CXX_STANDARD 17)

list(APPEND CMAKE_MODULE_PATH "${CMAKE_CURRENT_LIST_DIR}/cmake")


include(CMakeAddLib1)
include(CMakeAddLib2)

add_executable(cmake_libs src/main.cpp)

target_link_libraries(cmake_libs PUBLIC lib1 lib2)
