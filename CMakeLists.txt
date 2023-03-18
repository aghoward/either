cmake_minimum_required(VERSION 3.12)

project(Either)

add_library(either INTERFACE)
target_include_directories(either INTERFACE ${CMAKE_CURRENT_SOURCE_DIR}/include)
target_compile_options(either INTERFACE cxx_std_17)
