# ROS2wrapper-libsbp
## Things needed:
- [ ] ROS2
  - ROS2 Dockerfile 
- [ ] Swift Binary Protocol Client Libraries (libsbp)
- [ ] ROS2 wrapper for libsbp

## Current Approach
- using a ros2 docker image for a ros2 container
  - Dockerfile needed to set up the workspace and *probably* download libsbp plus create complete package
- git clone libsbp **OR**  download TAR Ball
  - [download from](http://swift-nav.github.io/libsbp/)
  - [source](http://wiki.ros.org/ROS/Tutorials/Wrapping%20External%20Libraries) for TAR Ball
- ROS2 wrapper to create a node on top of libsbp **to create ROS interfaces**
  - [source](https://roboticsbackend.com/create-a-ros-driver-package-introduction-what-is-a-ros-wrapper-1-4/)
- Create the package with the ROS2 wrapper
  - [source](https://roboticsbackend.com/create-a-ros-driver-package-package-and-test-your-driver-4-4/)
