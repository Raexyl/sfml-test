cmake_minimum_required(VERSION 3.10)

# set the project name
project(sfml-test VERSION 1.0)

# specify the C++ standard
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_EXTENSIONS OFF)
set(CMAKE_CXX_STANDARD_REQUIRED True)

if(NOT CMAKE_BUILD_TYPE)
  set(CMAKE_BUILD_TYPE Debug
    CACHE STRING "Choose the type of build (Debug or Release)" FORCE)
endif()

#subdirectories
add_subdirectory(src)
