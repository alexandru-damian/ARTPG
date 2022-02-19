cmake_minimum_required(VERSION 3.8)

project (
    Playground
    VERSION 0.0.0.1
    LANGUAGES CXX
    )

add_executable(${PROJECT_NAME} main.cpp)

set_target_properties(${PROJECT_NAME} PROPERTIES FOLDER ${PROJECT_NAME})