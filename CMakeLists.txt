cmake_minimum_required(VERSION 3.22)
project(kame
    VERSION 0.1.0
    LANGUAGES CXX
    DESCRIPTION "The Kame Programming Language"
)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

add_compile_options(-Wall -Wextra -Wpedantic)

add_executable(${PROJECT_NAME}
    main.cpp
)

include_directories(.)
