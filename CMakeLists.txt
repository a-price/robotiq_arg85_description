cmake_minimum_required(VERSION 2.8.3)
project(robotiq_arg85_description)

catkin_package()

install(DIRECTORY launch/
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}/launch
)

install(DIRECTORY meshes/
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}/meshes
)

install(DIRECTORY robots/
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}/launch
)

install(FILES urdf.rviz
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)
