# set project's name
PROJECT(hough)

###############################################################################
# CMake settings
CMAKE_MINIMUM_REQUIRED(VERSION 2.8.3)


find_package(OpenCV REQUIRED)

ADD_SUBDIRECTORY(src)


