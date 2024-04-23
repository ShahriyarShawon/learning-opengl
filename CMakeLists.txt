cmake_minimum_required(VERSION 3.3)

project(learnOpenGL CXX)
add_executable(getting_started_textures getting_started_textures/main.cpp)
set(LIBS glfw GLEW OpenGL)

target_link_libraries(getting_started_textures ${LIBS})

