cmake_minimum_required(VERSION 3.0.0)

add_library(header_only_lib INTERFACE)
target_include_directories(header_only_lib INTERFACE "lol")
target_link_libraries(${PROJECT_NAME} PRIVATE header_only_lib)
