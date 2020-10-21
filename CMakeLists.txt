cmake_minimum_required(VERSION 3.10.2)

project("ak_lab2" VERSION 0.1.0)
 
add_library(calculator STATIC calculator.cpp)
add_executable("${PROJECT_NAME}" main.cpp)
target_link_libraries("${PROJECT_NAME}" calculator)
