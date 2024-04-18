cmake_minimum_required(VERSION 3.3)

project(learnOpenGL CXX)
add_executable(hello_triangle hello_triangle.cpp)

target_link_libraries(hello_triangle glfw GLEW OpenGL)

