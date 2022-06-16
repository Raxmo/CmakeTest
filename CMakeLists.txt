cmake_minimum_required(VERSION 3.22.1)

project(CMAKETEST)

add_executable(${PROJECT_NAME} src/main.cpp)

add_subdirectory(src/thing)

target_link_libraries(${PROJECT_NAME} thing)
