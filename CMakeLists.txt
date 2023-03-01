cmake_minimum_required (VERSION 3.8.2)

project (gpmf-parser)

set(GMPF_PARSER_PUBLIC_INCLUDE_DIR ${CMAKE_CURRENT_LIST_DIR}/include)

add_subdirectory(${CMAKE_CURRENT_LIST_DIR}/src)
