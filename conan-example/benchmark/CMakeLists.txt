cmake_minimum_required(VERSION 3.15)
project(benchmark)

find_package(benchmark REQUIRED)

add_executable(${PROJECT_NAME} main.cpp)
target_link_libraries(${PROJECT_NAME} benchmark::benchmark)
