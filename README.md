# ecse373_f21_wcr25_lab2
lab 2 for ECSE373

To view the robot description without joint_state_publisher download the repository into the /src of a Catkin structured file.
Open a terminal and initialize for Ros melodic and then run roslaunch <name of ros package> launch_file.launch 
To launch using xacro you run the above command but add use_xacro:=true to the end.
To run state publisher gui run rosrun join_state_publisher.gui joint_state_publisher_gui & while launch_file was ran.

These files require Rviz. Rviz is ran with rosrun rviz rviz &
