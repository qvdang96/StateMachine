cmake_minimum_required(VERSION 2.8.9)
project(test)

include_directories( inc)

file(GLOB SOURCES "src/*.cpp")

add_executable(test ${SOURCES})