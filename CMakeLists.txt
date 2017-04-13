cmake_minimum_required(VERSION 3.6)
project(SSDsim)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES initialize.c avlTree.c avlTree.h flash.c flash.h initialize.h pagemap.c pagemap.h ssd.c ssd.h)
add_executable(SSDsim ${SOURCE_FILES})