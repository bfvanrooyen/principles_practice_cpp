cmake_minimum_required(VERSION 3.3)
project(Try_This)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES name_age.cpp)
add_executable(Try_This ${SOURCE_FILES})