cmake_minimum_required(VERSION 3.23.1)

project(zero-to-triangle)

add_executable(${PROJECT_NAME} glad.c main.cpp)

target_link_libraries(${PROJECT_NAME} GL dl glfw)
