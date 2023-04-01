cmake_minimum_required(VERSION 3.0.0)
project(mattsucks VERSION 0.1.0)
add_library(${PROJECT_NAME} STATIC)

target_sources(${PROJECT_NAME}
    PRIVATE
        xd/lol.h
)
