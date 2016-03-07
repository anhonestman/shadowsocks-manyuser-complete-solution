cmake_minimum_required(VERSION 3.3)
project(shadowsocks_manyuser_complete_solution)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES multiuser/main.c)
add_executable(shadowsocks_manyuser_complete_solution ${SOURCE_FILES})