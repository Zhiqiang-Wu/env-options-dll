cmake_minimum_required(VERSION 3.20)
project(env_options_dll)

set(CMAKE_CXX_STANDARD 23)

add_library(env-options SHARED library.cpp)
set_target_properties(env-options PROPERTIES PREFIX "")