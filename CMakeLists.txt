cmake_minimum_required(VERSION 2.8.12)
project(MyApplication)

set(CMAKE_MODULE_PATH ${CMAKE_MODULE_PATH} "${PROJECT_SOURCE_DIR}/modules/")
#find_package(SDL2 REQUIRED)
#find_package(Corrade REQUIRED)
#find_package(Magnum REQUIRED)

# tell CMake to search first in directories listed in CMAKE_MODULE_PATH
# when you use FIND_PACKAGE() or INCLUDE()
MESSAGE( STATUS "CMAKE_MODULE_PATH: " ${CMAKE_MODULE_PATH} )

add_subdirectory(src)
