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

## Rover Rules
1. Size, Weight, Power
    1. The rover shall be a stand-alone, off-the-grid, mobile platform. Tethered power and communications are not allowed. A single connected platform must leave the designated start gate. In the open field, the primary platform may deploy any number of smaller subplatforms, so long as the combined master/slave sub-platforms meet all additional requirements published. 
    2. Rovers shall be weighed by the judges during the set-up time of each mission. For weighing the rover must fit completely within a 1.2 m x 1.2 m box. Rovers may articulate/fold/bend to fit within the “transport crate,” but may not be disassembled to do so. This includes wheels, antenna, and any other system protruding from the rover. There 4s no vertical height limit for 2021, and the rover may be placed in any orientation.Failure to fit within the specified dimensions at weigh-in will result in a 40% penalty.
    3. The maximum allowable mass of the rover when deployed for any competition mission is 50 kg. The total mass of all fielded rover parts for all events is 70 kg. For example, a modular rover may have a robotic arm and a sensor that are never on the rover at the same time. The combinations of rover plus arm and rover plus sensor must each be under 50 kg, but the total rover plus arm plus sensor must be less than 70 kg. 
        - The weight limits do not include any spares or tools used to prepare or maintain the rover, but does include any items deployed by the rover such as sub-rovers, cameras,communication relays. 
        -  For each event in which the rover is overweight, the team shall be assessed a penalty of 5% of the points scored, per kilogram over 50.
    4. Rovers shall utilize power and propulsion systems that are applicable to operations on Mars. Air-breathing systems are not permitted: No power or propulsion system may ingest ambient air for the purpose of combustion or other chemical reaction that yields energy. 
    5. No airborne vehicles or lighter-than-air systems are allowed for 2021. 
    6. All rovers shall have a “kill switch” that is readily visible and accessible on the exterior of the rover. This switch shall immediately stop the rover’s movement and cease all power draw from batteries in the event of an emergency such as a battery fire.
2. Communications Equipment
3. Restrictions on the 900 MHz and 2.4GHz bands
4. Interventions