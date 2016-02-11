cmake_minimum_required(VERSION 2.8.4)
project(c_lane_detection)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS}")

add_custom_target(c_lane_detection COMMAND make -C ${c_lane_detection_SOURCE_DIR}
                         CLION_EXE_DIR=${PROJECT_BINARY_DIR})
