cmake_minimum_required(VERSION 3.10)
project(unt C)

set(CMAKE_C_STANDARD 17)

add_executable(unt
        src/main.c
        src/monitor.c
)

target_include_directories(unt PRIVATE include)