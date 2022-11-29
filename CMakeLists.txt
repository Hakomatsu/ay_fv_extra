cmake_minimum_required(VERSION 3.0.2)
project(ay_fv_extra)

find_package(catkin REQUIRED COMPONENTS
  fingervision
  )

catkin_package(
  CATKIN_DEPENDS fingervision
  )
include_directories(
  ${catkin_INCLUDE_DIRS}
  )
