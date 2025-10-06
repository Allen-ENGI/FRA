cmake_minimum_required(VERSION 3.5)
project(kuka_kr3_description)

find_package(ament_cmake REQUIRED)

install(DIRECTORY urdf config data
  DESTINATION share/${PROJECT_NAME})

ament_package()
