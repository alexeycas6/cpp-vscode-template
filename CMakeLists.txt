cmake_minimum_required(VERSION 3.15)
project(main_project LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 20)

include_directories(${CMAKE_SOURCE_DIR}/src)

set(SOURCES_DIR ${CMAKE_SOURCE_DIR}/src)
set(SOURCES_FILES
 ${SOURCES_DIR}/main.cpp
)

add_executable(main_project ${SOURCES_FILES})