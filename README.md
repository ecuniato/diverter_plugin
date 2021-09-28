Diverter Plugin
==============

This is a Gazebo plugin to simulate the presence of a power line.
The power line is not visible in simulation but it will exert forces on the drone arm's tip one the power line altitude is reached. This altitude can be customized inside the code by modifying the parameter Z_CABLE in the code 

Compile the plugin with catkin_make and add it to your world file (it is a WorldPlugin).