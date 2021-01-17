Instructions to Setup and Run my_simulation:
TO CREATE A CATKIN WORKSPACE:
1. Open terminal and enter below commands
    mkdir -p ~/project2_ws/src
    cd ~/project2_ws/src
    catkin_init_worksapce
    catkin_create_pkg my_simulation catkin
    cd my_simulation
2. Open Git Bash/Terminal from a new directory.
3. Clone the project from git reository using command : Git clone "https://github.com/Meeakshi/PDE4420_FinalProject.git"
4. Switch to master branch using command "Git Checkout master".
5. Open new tab of terminal and enter command 
    export TURTLEBOT3_MODEL=waffle
    roslaunch my_simulation my_world.launch
6. Rviz and Gazebo will launch with TurtleBot3.
7. Open another terminal and enter
    Rosrun my_simulation waypoint.py
8. Turtlebot3 will start moving in a waypoint scripted in the waypoint.py file.



