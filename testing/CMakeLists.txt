cmake_minimum_required(VERSION 2.8)
project( test )
find_package( OpenCV REQUIRED )
add_executable( test HoughLines_Demo.cpp)
target_link_libraries( test ${OpenCV_LIBS} )
