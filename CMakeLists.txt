cmake_minimum_required(VERSION 2.8.3)
project(scara_description)


find_package(catkin REQUIRED COMPONENTS
  message_generation
  roscpp
  rospy
  std_msgs
  geometry_msgs
  urdf
  xacro
  message_generation
)

catkin_package(
  CATKIN_DEPENDS
    geometry_msgs
    roscpp
    rospy
    std_msgs
)

include_directories(
# include
  ${catkin_INCLUDE_DIRS}
)