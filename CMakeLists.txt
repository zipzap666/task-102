cmake_minimum_required(VERSION 3.14)

project(tests LANGUAGES CXX)

add_subdirectory(src/proto)
add_subdirectory(src/parser)

enable_testing()
add_subdirectory(test)