cmake_minimum_required(VERSION 2.8)

project( Example )
find_package( OpenCV REQUIRED )
include_directories( ${OpenCV_INCLUDE_DIRS} )
add_executable( Example main.cpp )
target_link_libraries( Example ${OpenCV_LIBS} )