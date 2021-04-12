cmake_minimum_required(VERSION 2.10)

project(network)

set(CMAKE_CXX_STANDARD 11)

add_executable(network network.cpp)

target_link_libraries(network curl)