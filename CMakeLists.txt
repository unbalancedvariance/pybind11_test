cmake_minimum_required(VERSION 3.4...3.18)
project(pybind_test LANGUAGES CXX)

add_subdirectory(pybind11)

pybind11_add_module(somecode somecode.cpp)
