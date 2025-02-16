cmake_minimum_required(VERSION 3.10)
project(MPSS)

set(CMAKE_CXX_STANDARD 17)

include_directories(${CMAKE_SOURCE_DIR}/util)

add_executable(MPSS
    main.cpp)
