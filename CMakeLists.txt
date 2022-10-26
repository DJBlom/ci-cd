cmake_minimum_required(VERSION 3.2)

set(CMAKE_EXPORT_COMPILE_COMMANDS ON)
set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall -Werror -fopenmp -O3")
project(test VERSION 1.0.0 LANGUAGES CXX)


add_executable(main
    main.cpp
)
