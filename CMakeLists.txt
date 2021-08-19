cmake_minimum_required(VERSION 3.20)

project(jr_socket)

add_library(jr_socket STATIC jr_socket.c jr_socket.h)
target_include_directories(jr_socket PUBLIC .)
set(CMAKE_C_STANDARD 11)
set(CMAKE_C_STANDARD_REQUIRED ON)
set(CMAKE_BUILD_TYPE Debug)