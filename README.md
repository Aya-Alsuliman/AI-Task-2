# AI-Task-2
            SLAM Simulation Using Turtlebot3
             
Robotic Movement is one of the most essential parts while building your robot.

This process consists of four steps: 1-Positioning  2-Sensing 3-Mapping 4-Path.

To accomplish the previous steps the robot will do SLAM.

SLAM: Simultaneous localization and mapping.

For the sensing part, we will use a Lidar laser scanner. 

But before working on real, we need to build and test our progress.

Simulation is the key.

as a startup, we will use turtlebot3 simulation.

First, download the dependencies packages

<img width="677" alt="image" src="https://github.com/Aya-Alsuliman/AI-Task-2/assets/139065454/46717967-ef05-4a16-bf5c-dd3bdd797638">


Second, download the TurtleBot3 packages

<img width="674" alt="image" src="https://github.com/Aya-Alsuliman/AI-Task-2/assets/139065454/e957f3d5-37c0-42f6-b45b-bb4a6b8432b0">
 
Third, install the Gazebo simulation package. 

<img width="658" alt="image" src="https://github.com/Aya-Alsuliman/AI-Task-2/assets/139065454/9caa1675-5d18-48a1-a1a5-70bc2b656ffb">

 
Then, install the TurtleBot3 World 

<img width="643" alt="image" src="https://github.com/Aya-Alsuliman/AI-Task-2/assets/139065454/3496e693-838c-444c-b0df-177a74275d6a">


Now Gazebo will open with TurtleBot3 World, but we still cannot see 2-D Gmapping!


To extract the SLAM mapping, we will run the SLAM Node


<img width="579" alt="image" src="https://github.com/Aya-Alsuliman/AI-Task-2/assets/139065454/f46acdfb-79fa-41f7-a108-8a8856a7c4f7">


Now, RVis will open with the TurtleBot3 World map 

![صورة11](https://github.com/Aya-Alsuliman/AI-Task-2/assets/139065454/20f84c3b-fcf1-4648-a20e-72ded6e3ddd7)


But it is obvious that a major part of the map is missing! That's because the robot didn't move around the TurtleBot3 World, so it didn't scan the map yet.

To control the movement of the robot, we need to run the Teleoperation Node using the following commands

<img width="648" alt="image" src="https://github.com/Aya-Alsuliman/AI-Task-2/assets/139065454/4cf8f4a0-9d01-4dc6-afe8-9fc153f84b80">


While we move the robot around, it will simultaneously localization and mapping as shown in the video below



https://github.com/Aya-Alsuliman/AI-Task-2/assets/139065454/1eb72990-e40c-4237-85b6-cc5dfb07274c


Finally, to save this map we use the following command

<img width="647" alt="image" src="https://github.com/Aya-Alsuliman/AI-Task-2/assets/139065454/e776ffb9-1001-4214-8eac-7cfa662bf83f">

You can find attached the map.pgm file  








