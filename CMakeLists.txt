cmake_minimum_required(VERSION 2.8.3)
project(freeplay_sandbox_supervisor)

## Find catkin macros and libraries
## if COMPONENTS list like find_package(catkin REQUIRED COMPONENTS xyz)
## is used, also find other catkin packages
find_package(catkin REQUIRED COMPONENTS
  roslaunch
  rospy
)

catkin_package(
#  INCLUDE_DIRS include
#  LIBRARIES freeplay_sandbox_supervisor
#  CATKIN_DEPENDS roslaunch rospy
#  DEPENDS system_lib
)

catkin_python_setup()

