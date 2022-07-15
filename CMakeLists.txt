cmake_minimum_required(VERSION 3.21)
project(HomeWork27_3)

set(CMAKE_CXX_STANDARD 14)

add_executable(HomeWork27_3 src/main.cpp include/boss.h include/employee.h include/manager.h src/boss.cpp src/manager.cpp)
