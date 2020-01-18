cmake_minimum_required(VERSION 3.10)

project(CoordinateTransformation VERSION 0.1.0)

add_subdirectory(app)
add_subdirectory(lib)
add_subdirectory(src)
add_subdirectory(test)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)
