cmake_minimum_required(VERSION 3.15)
project(NNSearchTree)

set(CMAKE_CXX_STANDARD 14)

include_directories(include)

add_executable(NNSearchTree benchmark.cpp include/bst.hpp include/resultSet.hpp include/kdtree.hpp include/test.hpp include/octree.hpp include/benchmark.hpp)
