cmake_minimum_required(VERSION 2.8.3)
project(fetch_velodyne)
find_package(catkin REQUIRED COMPONENTS
  roscpp
  rospy
)
include_directories(
  ${catkin_INCLUDE_DIRS}
)
