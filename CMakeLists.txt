cmake_minimum_required(VERSION 2.8.12.2)

project(Genetic_Algorithm)

add_definitions(-std=c++11)

#add_definitions(-Wall)

include_directories(include)

set(SRCGA src/main.cpp)

add_executable(./../bin/GAs ${SRCGA})
