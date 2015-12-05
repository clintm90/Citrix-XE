cmake_minimum_required(VERSION 3.3)
project(Citrix_XE)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp Citrix.cpp Citrix.h)
add_executable(Citrix_XE ${SOURCE_FILES})