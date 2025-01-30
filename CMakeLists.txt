cmake_minimum_required(VERSION 3.30)
project(rubiks_cube_solver)

set(CMAKE_CXX_STANDARD 20)

add_executable(rubiks_cube_solver main.cpp
        genericRubiksCube.cpp
        genericRubiksCube.h)
