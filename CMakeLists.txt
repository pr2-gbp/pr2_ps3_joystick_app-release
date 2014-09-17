cmake_minimum_required(VERSION 2.8.3)
project(pr2_ps3_joystick_app)
find_package(catkin REQUIRED COMPONENTS pr2_teleop_general)

catkin_package(
    DEPENDS pr2_teleop_general
    CATKIN_DEPENDS # TODO
    INCLUDE_DIRS # TODO include
    LIBRARIES # TODO
)

install(FILES ps3_joy.png pr2_ps3_joystick.app pr2_ps3_joystick.interface DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})

