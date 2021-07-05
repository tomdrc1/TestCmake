cmake_minimum_required(VERSION 3.14.0)
set(PROJECT_NAME "TestCmake")

project(${PROJECT_NAME} VERSION 1.0.0)

set(CMAKE_CXX_STANDARD 17)
file(GLOB TestCmake_SRC 
	src/*.cpp
	src/*.h
)

add_executable(${PROJECT_NAME} ${TestCmake_SRC})
