cmake_minimum_required(VERSION 3.3)

project(learnOpenGL CXX)
add_executable(out main.cpp)

#find_package(glfw3 REQUIRED)
target_link_libraries(out glfw)

#find_package(GLEW REQUIRED)
target_link_libraries(out GLEW)

#find_package(OpenGL REQUIRED)
target_link_libraries(out OpenGL)

