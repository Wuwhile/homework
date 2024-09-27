cmake_minimum_required(VERSION 3.29)

project(Helloworld LANGUAGES CXX C)

add_executable(main
    src/main.cpp
    src/a.cpp
)

target_include_directories(main PRIVATE include)