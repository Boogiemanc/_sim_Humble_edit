# Ducktape Humble
- As the name suggest is the eufs_sim with minor script edit so it could run as intended on [RO2 Humble](https://docs.ros.org/en/humble/index.html)
- all the required packages(ackermann_msgs,eufs_msgs,eufs_sim) are included in src folder
- 
# Whats inclued
- Ackermann Msgs
- Edited eufs_sim file

# Changes
- instead of `tf2::convert()` -> use `transform.getOrigin()` and `transform.getRotation()` to get the car model's position and orientation
- values inside widget.setGeometry() are now `integers`instead of `float`


# Steps to launch the sim:
- Read the offcial wiki on how to [launch the sim](https://gitlab.com/eufs/eufs_sim/-/wikis/Getting-Started-Guide)
- remember to .install/setup.bash after build
- Enjoy

  
