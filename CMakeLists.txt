cmake_minimum_required (VERSION 3.0)

project(myProgram)

include_directories(include)

file(GLOB SOURCES "src/*.cpp")
add_executable(myProgram ${SOURCES})


