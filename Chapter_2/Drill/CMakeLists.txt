cmake_minimum_required(VERSION 3.3)
project(Hello_World)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES hello_world.cpp)
add_executable(Hello_World ${SOURCE_FILES})