# C++ and CMake versions.
cmake_minimum_required(VERSION 3.16.3)
set(CMAKE_CXX_STANDARD 17)

# Name of our executable and project.
set(NAME VulkanPathTracer)
project(${NAME})

include_directories("${PROJECT_SOURCE_DIR}/src")
file(GLOB SOURCES "src/*cpp")