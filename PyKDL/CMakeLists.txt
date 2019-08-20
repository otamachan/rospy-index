cmake_minimum_required(VERSION 2.6)

add_subdirectory(orocos_kinematics_dynamics/orocos_kdl)
include_directories(
  ${CMAKE_CURRENT_SOURCE_DIR}
  ${CMAKE_CURRENT_BINARY_DIR}/orocos_kinematics_dynamics/orocos_kdl/src)
add_subdirectory(orocos_kinematics_dynamics/python_orocos_kdl)
