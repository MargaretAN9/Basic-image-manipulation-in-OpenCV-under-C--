cmake_minimum_required(VERSION 2.8)
project( BasicImageManipulation )
find_package( OpenCV REQUIRED )
add_executable( BasicImageManipulation main.cpp )
target_link_libraries( BasicImageManipulation ${OpenCV_LIBS} )