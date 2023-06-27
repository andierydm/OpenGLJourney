cmake_minimum_required(VERSION 3.2)
project(reading_glsl_source_from_files)

add_executable(main main.cpp)

target_link_libraries(main GL)
target_link_libraries(main GLEW)
target_link_libraries(main glfw)