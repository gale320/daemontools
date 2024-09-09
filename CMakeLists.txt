cmake_minimum_required(VERSION 3.20)
project(ademontools C)


include(cmake/option.cmake)

include_directories(src)

add_subdirectory(src)
add_subdirectory(app)

