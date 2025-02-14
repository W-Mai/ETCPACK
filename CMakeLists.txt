cmake_minimum_required(VERSION 3.18)

project(ETCPack CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

file(GLOB source
    "source/*.cxx"
    "source/*.h"
)

add_executable(etcpack ${source})
