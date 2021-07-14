# Oryks Rover - A Mars Rover based on ROS

![orykrover assembly](https://github.com/lyleokoth/oryksRover/blob/main/src/rover_description/CAD/Pictures/Mars%20Rover.JPG)

This repository contains all the files and code needed to simulate and build the oryksrover, a six wheeled Mars Rover robot, using [Gazebo](http://gazebosim.org/)  and [ROS](https://www.ros.org/).
The software runs on [ROS noetic](http://wiki.ros.org/noetic) and [Ubuntu 20.04](http://www.releases.ubuntu.com/20.04/). If you want to use a different ROS version, you might have to do some changes to the source code.
The repo also contains the firmware needed to set up the robot, i.e the motor controller as well as the code for reading other sensors such as the IMU.

## The Motivation

The aim was to come up with an affordable design that can be used by other University students when participating in the [URC](http://urc.marssociety.org/) challenge based on [The Robot Operating System(ROS)](https://www.ros.org/). The design of oryks rover was mainly influenced by the pricing and ease of assembly. As such, the parts are either easily 3d printed and drilled for connections or available off-the-shelf. I hope this project can act as a starting point for other University Students aiming to participate in the competition.

## The University Rover Challenge

The University Rover Challenge (URC) is the world's premier robotics competition for college students.  Held annually in the desert of southern Utah in the United States, URC challenges student teams to design and build the next generation of Mars rovers that will one day work alongside astronauts exploring the Red Planet.
 
URC was launched in 2006, with competitions being held every summer since 2007.  URC consistently draws an international field of the most talented and promising students around.  If you're a college student interested in robotics and Mars exploration, the only question left is...
 
####                        Are you up for the Challenge?!