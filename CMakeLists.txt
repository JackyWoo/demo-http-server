cmake_minimum_required(VERSION 3.17)
project(demo_http_server)

set(CMAKE_CXX_STANDARD 20)

set (USE_INTERNAL_POCO_LIBRARY TRUE)

add_subdirectory(src)
add_subdirectory(poco-cmake)
