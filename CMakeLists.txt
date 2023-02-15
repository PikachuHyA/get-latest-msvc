cmake_minimum_required(VERSION 3.15)
set(CMAKE_EXPORT_COMPILE_COMMANDS ON)
project(msvc-test
        LANGUAGES CXX
        )
add_executable(main main.cpp)