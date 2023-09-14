cmake_minimum_required(VERSION 3.26)
project(Concurency)

set(CMAKE_CXX_STANDARD 17)

add_executable(Concurency main.cpp test_framework.h)

target_link_libraries(Concurency PRIVATE pthread)
