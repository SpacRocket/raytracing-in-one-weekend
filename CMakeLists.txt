cmake_minimum_required(VERSION 3.25)
project(raytracer)
set(CMAKE_CXX_STANDARD 23)

# Add main.cpp file of project root directory as source file
set(SOURCE_FILES main.cpp)

# Add executable target with source files listed in SOURCE_FILES variable
add_executable(simple_example ${SOURCE_FILES})
target_include_directories(simple_example PUBLIC includes)