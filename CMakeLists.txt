cmake_minimum_required(VERSION 3.10)
project(distlink)

add_library(distlink STATIC "src/distlink.cpp" "src/distlink.h")
set(CMAKE_LIBRARY_OUTPUT_DIRECTORY ${PROJECT_BINARY_DIR}/lib)