cmake_minimum_required(VERSION 4.0)
project(nippon)

set(CMAKE_CXX_STANDARD 20)

add_executable(nippon
        src/main.cpp
        src/tokenization.h
        src/parser.h
        src/generation.h
        src/arena.h)
