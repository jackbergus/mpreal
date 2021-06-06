cmake_minimum_required(VERSION 3.16)
project(mpreal)

set(CMAKE_CXX_STANDARD 20)

add_executable(mpreal example/example.cpp)
target_link_libraries(mpreal mpfr gmp)

