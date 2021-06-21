cmake_minimum_required (VERSION 2.8.11)
project (DEMO)

find_package(Threads REQUIRED)

add_executable(demo demo_proj_cpp.cpp)
