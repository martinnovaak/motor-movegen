cmake_minimum_required(VERSION 3.28)
project(pseudolegal)

set(CMAKE_CXX_STANDARD 20)

add_executable(pseudolegal main.cpp
        chess/bits.hpp
        chess/types.hpp
        chess/pinmask.hpp
        chess/fen_utils.hpp)