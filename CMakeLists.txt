cmake_minimum_required(VERSION 3.25)
project(daf_res)

set(CMAKE_CXX_STANDARD 14)

add_executable(daf_res
        src/code/main.cpp
        src/code/GetImageData.cpp)
