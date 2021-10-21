cmake_minimum_required(VERSION 3.20)
project(untitled1)

set(CMAKE_CXX_STANDARD 17)
include_directories(inc)
add_executable(laba_7 main.cpp
        src/Write.cpp
        src/Read.cpp
        src/Rabota_nad_mass.cpp)
