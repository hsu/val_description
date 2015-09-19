#Project Name - val_description
#Maintainer - Jordan Lack - jordan.t.lack@nasa.gov - jlack1987@gmail.com

The val_description package contains the files needed to generate an URDF for Valkyrie as well as the meshes for visualization. Also contained in the val_description are xacro files for generating Valkyrie instance files. Valkyrie instance files are xml files that contain information about the hardware(actuators, shared memory nodes, sensors, etc). Some of this information is shared between the URDF and instance files. With this, the various coefficient files are included.

#Usage Instructions
If you don't have ROS installed, shimmy over to [here](http://wiki.ros.org/indigo/Installation/Ubuntu) and install ROS(you don't need to install all of ROS if you don't want to, but you at least need [catkin](http://wiki.ros.org/catkin)). Once you have done this, clone the val_description repo in your catkin workspace. The URDF is then generated by:
```bash
cd <path_to_your_catkin_workspace> 
catkin_make
```
The URDF will be in the directory <val_description>/urdf

#Credits
- Johnson Space Center - ER4 - Valkyrie Team
- IHMC humanoids group
- Maurice Fallon and his group
- Open Source Robotics Foundation(OSRF)

#License
NASA 1.3