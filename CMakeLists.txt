cmake_minimum_required(VERSION 3.1)
project(loghin-toolbox)

set(CMAKE_CXX_STANDARD 14)
include_directories(include)

add_executable(
    stringSample 
    main.cpp
    src/String.cpp
    include/String.h
    src/Array.cpp
    include/Array.h
    include/types.h
)

add_executable(
    matrixSample
    matrixTest.cpp
    include/Matrix.h
)