# PDE4420_FinalProject
Requirment:
In the final module project you will simulate a wheeled robot in a Gazebo virtual environment to move to a specified location. This motion is instructed by a node which publishes the moving command to drive the robot base. You will prepare a research report to outline your design in, but not limited to, the URDF, message transfer mechanism between publisher and subscriber, simulation in Gazebo and displaying in rviz, navigation, and coordinate frames transformation, etc. This project will be used as an overall evaluation of your learning performance, and covers the main learning outcomes in the module.

Outcome:
In this project report I have achieved knowledge on integration of ROS, URDF, Rviz and Gazebo to spawn a robot in a virtual environment. I could successfully build a world and familiarize turtlebot in its world. Could also programmatically move the bot in a waypoint using python programming language. This report will help reader to practice step by step on how to install ROS, create catkin work space, how to create a package, to create a gazebo world and to launch a robot in the world and make it move around in the path we define. 

Instructions to Setup and Run my_simulation:

1. Open terminal and enter below commands mkdir -p ~/project2_ws/src cd ~/project2_ws/src catkin_init_worksapce catkin_create_pkg my_simulation catkin cd my_simulation
2. Open Git Bash/Terminal from a new directory.
3. Clone the project from git reository using command : Git clone "https://github.com/Meeakshi/PDE4420_FinalProject.git"
4. Switch to master branch using command "Git Checkout master".
5. Open new tab of terminal and enter command export TURTLEBOT3_MODEL=waffle roslaunch my_simulation my_world.launch
6. Rviz and Gazebo will launch with TurtleBot3.
7. Open another terminal and enter Rosrun my_simulation waypoint.py
8. Turtlebot3 will start moving in a waypoint scripted in the waypoint.py file.
