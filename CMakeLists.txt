cmake_minimum_required(VERSION 3.2)

project(Nbody-cpp)

add_library(GLFW IMPORTED)
set_property(TAGRET GLFW PROPERTY IMPORTED_LOCATION ./libs/glfw)

target_sources(GLFW
    PRIVATE "libs/glfw/src")
target_include_directories(GLFW     
    PUBLIC "libs/glfw/include")

target_sources(GLEW
    PRIVATE "libs/glew/src")
target_include_directories(GLFW     
    PUBLIC "libs/glew/include"))