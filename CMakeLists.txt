cmake_minimum_required(VERSION 4.1)
project(MandlebrotSet)

set(CMAKE_CXX_STANDARD 20)

add_executable(MandlebrotSet main.cpp)
find_package(raylib CONFIG REQUIRED)
target_link_libraries(MandlebrotSet PRIVATE raylib)