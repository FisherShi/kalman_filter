cmake_minimum_required(VERSION 3.6)
project(kalman_filter)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp kalman_filter.cpp kalman_filter.h tracking.cpp tracking.h measurement_package.h ground_truth_package.h)
add_executable(Kalman_filter ${SOURCE_FILES})