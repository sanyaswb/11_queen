cmake_minimum_required(VERSION 3.23)
project(11_queen)

set(CMAKE_CXX_STANDARD 14)

add_executable(11_queen main.cpp index.cpp test/test.h test/test.cpp index.h)
