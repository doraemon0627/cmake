#It will be compiled with CC (default c compiler) and conpiler options are gcc's options
#so if your CC is not gcc, I'm not sure it will work.

cmake_minimum_required(VERSION 3.10)

add_compile_options(-Wall -Wpedantic -pedantic)

set(CMAKE_BUILD_TYPE Debug)

set(CMAKE_C_STANDARD 11)

add_executable(main main.c)

