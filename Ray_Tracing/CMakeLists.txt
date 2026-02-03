cmake_minimum_required(VERSION 3.26.0)
project(Ray_Tracing VERSION 1.0.0)

# adding source files to our exectuable programs
add_executable(ray01 src/main.cpp)

# specify include directories
target_include_directories(ray01 PRIVATE include )