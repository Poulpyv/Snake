CMAKE_MINIMUM_REQUIRED(VERSION 3.0)

project(Snake_Game)

SET(GCC_COVERAGE_COMPILE_FLAGS "-Wall -pedantic -std=c++17")
add_definitions(${GCC_COVERAGE_COMPILE_FLAGS})

include_directories(${CMAKE_CURRENT_SOURCE_DIR}/include)
set(SOURCES ${CMAKE_CURRENT_SOURCE_DIR}/source/main.cpp)

add_executable(${PROJECT_NAME} ${SOURCES})
