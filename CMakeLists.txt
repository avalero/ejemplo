cmake_minimum_required(VERSION 3.12)
project(Ejemplo)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_COMPILER g++ -std=c++20)

# Add your source files here
set(SOURCES
  hola.cpp
)


# Create the executable
add_executable(miejemplo ${SOURCES})
