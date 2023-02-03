include_directories(${CMAKE_CURRENT_BINARY_DIR})

add_library(
    parser parserTools.hpp
)

target_link_libraries(parser PUBLIC proto)