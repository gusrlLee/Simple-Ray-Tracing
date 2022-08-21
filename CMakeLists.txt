cmake_minimum_required(VERSION 3.0)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
project(Simple_RayTracing)


add_executable(${PROJECT_NAME} 
    src/pi.cpp
)

include_directories(include)
