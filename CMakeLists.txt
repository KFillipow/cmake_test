cmake_minimum_required(VERSION 3.10)

SET(CMAKE_C_COMPILER /usr/bin/gcc)
SET(CMAKE_CXX_COMPILER /usr/bin/g++)

# set project name
project(cmake_test)

#add sources
file(GLOB SOURCES "src/*.c")

add_executable(testcmake ${SOURCES})
