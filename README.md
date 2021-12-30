# hdm_robotarm01_moveit
This package implement MoveIt on the hdm_robotarm01 package.
Run the following command to spawn the robot arm with joint_trajectory_controllers in a gazebo world
```
roslaunch hdm_robotarm_01 gazebo_world_moveit.launch
```
Next, run the following command to start RViz and start motion planning
```
roslaunch hdm_robotarm01_moveit moveit_planning_execution.launch 
```
