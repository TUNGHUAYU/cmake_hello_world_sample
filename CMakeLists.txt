cmake_minimum_required(VERSION 2.4)

project(hello)
include_directories(${PROJECT_SOURCE_DIR})

add_executable(app main.c foo.c)

