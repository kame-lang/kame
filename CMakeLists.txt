cmake_minimum_required(VERSION 4.1.1)
project(kame
    VERSION 0.1.0
    LANGUAGES C
    DESCRIPTION "The Kame programming language"
)

set(CMAKE_C_STANDARD 11)
set(CMAKE_C_STANDARD_REQUIRED ON)
set(CMAKE_EXPORT_COMPILE_COMMANDS ON)
set(CMAKE_C_EXTENSIONS OFF)

add_compile_options(-Wall -Wextra -Wpedantic)

add_executable(${PROJECT_NAME}
    main.c
)
