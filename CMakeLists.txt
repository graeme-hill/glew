cmake_minimum_required(VERSION 3.5.1)
project(glew)

#include_directories(include)

add_library(glew src/glew.c)
target_include_directories(glew PUBLIC include)
