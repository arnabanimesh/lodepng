cmake_minimum_required(VERSION 3.10)
project(lodepng VERSION 2024.04.15 LANGUAGES CXX)
add_library(${PROJECT_NAME} STATIC lodepng.cpp)
target_include_directories(${PROJECT_NAME} PRIVATE ${CMAKE_CURRENT_SOURCE_DIR})