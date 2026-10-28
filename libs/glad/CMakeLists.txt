cmake_minimum_required(VERSION 3.16...3.28 FATAL_ERROR)

project(GLAD VERSION 2.0.0)

add_library(GLAD)
target_include_directories(GLAD 
    INTERFACE
    "./include"
)




