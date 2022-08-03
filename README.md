# robotArm-download-run-

## Install arm backage in catkin_ws file:

> > `cd ~/catkin_ws/`

> > `catkin_make`

> > `cd ~/catkin_ws/src`


## go to robot arm backages that we will work on it:

> > `git clone https://github.com/smart-methods/arduino_robot_arm.git`

> > `cd ~/catkin_ws`


## download the Commands that are needed from ros

> > `rosdep install --from-paths src --ignore-src -r -y`

> > `sudo apt-get install ros-kinetic-moveit`

> > `sudo apt-get install ros-kinetic-joint-state-publisher ros-kinetic-joint-state-publisher-gui`

> > `sudo apt-get install ros-kinetic-gazebo-ros-control joint-state-publisher`

> > `sudo apt-get install ros-kinetic-ros-controllers ros-kinetic-ros-control`

> > `sudo nano ~/.bashrc`

> > **at the end of the (bashrc) file add the follwing line (don't forget to put your OS name!!!**
`source /home/!!OS NAME!!/catkin_ws/devel/setup.bash`
then from the keyboard:
> > ctrl + o
> > enter
> > ctrl + x


## to update source of bashrc file
> > `source ~/.bashrc`


## to run reves on ros (the simulator)
> > `roslaunch robot_arm_pkg check_motors.launch`
