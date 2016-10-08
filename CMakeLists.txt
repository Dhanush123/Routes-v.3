cmake_minimum_required(VERSION 3.6)
project(Routes_v_3)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall -std=c++11")

set(SOURCE_FILES Route3.cpp)
add_executable(Routes_v_3 ${SOURCE_FILES})