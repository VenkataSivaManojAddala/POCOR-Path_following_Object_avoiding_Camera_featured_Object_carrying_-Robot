# POCOR-Path_following_Object_avoiding_Camera_featured_Object_carrying_Robot

## Description
This is a project that involves a robot built on the ROS2 (Robot Operating System 2) framework with the simulation in gazebo. The robot is designed to perform several tasks including path following, object avoidance, and carrying objects and also has a camera feature to the bot.

## Requirements:
* Ubuntu 22.04
* ROS2-HUMBLE
* Gazebo
* rviz2

## Process to run the robot:
Open a new terminal in the workspace directory, run the following command <br>
<code> ros2 launch pocor launch_sim.launch.py world:=./src/pocor/worlds/final_worl.world</code> <br>
Open a another new terminal window in the same workspace directory and run the following command <br>
<code> ros2 launch pocor path_navigation_launch.py</code> <br>
Open a another termial window in the same workspace, and change the path to <code> /src/pocor/scripts </code>, run the below command:<br>
<code>python3 path1.py</code>
Path can be changed by replacing the the above path1.py script file with the respected the path file. 
 
## Implementation:
* Robot model:
<code>![Screenshot from 2023-06-27 19-15-50](https://github.com/VenkataSivaManojAddala/POCOR-Path_following_Object_avoiding_Camera_featured_Object_carrying_-Robot/assets/119154773/37680374-4fe7-4d70-8810-778b556f0d2e)
</code>
* World:
  <code> ![Screenshot from 2023-06-27 19-42-16](https://github.com/VenkataSivaManojAddala/POCOR-Path_following_Object_avoiding_Camera_featured_Object_carrying_-Robot/assets/119154773/89900f86-f250-407f-8128-c46803598f18)
</code>
* Camera View:
  <code> ![Screenshot from 2023-06-27 19-18-44](https://github.com/VenkataSivaManojAddala/POCOR-Path_following_Object_avoiding_Camera_featured_Object_carrying_-Robot/assets/119154773/92d3560a-d83c-49ab-b992-54ac057b8171)
</code>
* Map:
  <code>![Screenshot from 2023-06-27 19-17-54](https://github.com/VenkataSivaManojAddala/POCOR-Path_following_Object_avoiding_Camera_featured_Object_carrying_-Robot/assets/119154773/8c6df481-b783-40d3-9e0e-7b5448074b74)
</code>
* Implementatiom:
  <code><img width="1184" alt="Screenshot 2023-06-27 at 10 16 07 PM" src="https://github.com/VenkataSivaManojAddala/POCOR-Path_following_Object_avoiding_Camera_featured_Object_carrying_-Robot/assets/119154773/83bdada8-d3ce-468f-a091-b0d397d6b8a1">
</code>

## Sample Video of implementation:
In the following video, the path is given from the initial pose of the robot to post office.

