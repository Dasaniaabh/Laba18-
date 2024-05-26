cmake_minimum_required(VERSION 3.26)
project(Labaratornaia_18 C)

set(CMAKE_C_STANDARD 11)

add_executable(Labaratornaia_18
        test.c
        libs/data_struct/string/string.c
        libs/data_struct/string/string.h
        main.c)

add_subdirectory(libs)

target_link_libraries(data_struct)
