cmake_minimum_required(VERSION 3.21)
project(CircBuffer)

set(CMAKE_CXX_STANDARD 17)

add_executable(Lab3 main.cpp CircularIterator.h CircularBuffer.h Circular.hpp algo.h CRational.cpp CRational.h)
