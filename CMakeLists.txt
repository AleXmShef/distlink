cmake_minimum_required(VERSION 3.10)

project(distlink)
set(CMAKE_ARCHIVE_OUTPUT_DIRECTORY ${CMAKE_SOURCE_DIR}/lib)
add_library(distlink STATIC "src/distlink.cpp" "src/distlink.h")
