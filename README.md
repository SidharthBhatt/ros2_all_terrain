This is a NSF Iot4AG REU Project 

Background: 
One of the goals of the oat's center is to have a fully automated farm system with a tractor, drones, ground sensors, etc all speaking together. In order to facilitate this, they all need to communicate together. The current plan is to use ROS, which is a popular robotics library. Before coding the tractor, we are planning to use the mini robot as a testbed to explore ROS. We want to be able to scan our surroundings, pathfind, and complete complex tasks using the robot. We plan to create demos that showcase the robot's functionality. Then once we understand how to do that, we can move onto the Polaris Ranger. So far, I have tried to emulate the robot in simulation, constructed the robot, become familiar with its code, created a repository, and I am in the process of making it move with code. One of the example demos we want to complete is making the robot scan the lab area, and go from one side to the other.

Steps to Connect to the Robot: 
Ensure the robot is on by switching all switches on 
Wait 2-3 minutes for the robot to boot up 
connect to the ROSMASTER Wifi (password yahboom)
ssh into the robot (ssh jetson@192.168.1.11), the IP is displayed on the robots screen 
Password is yahboom 
(Optional) you can connect to wifi by turning on your hotspot on your phone and connecting it over USB to your computer, this is the best solution I have found so far 

Other Details: 
Do NOT under any circumstances charge the battery and use the robot at the same time. (we have been warned the battery may explode)
If the robot starts beeping after you turn on, the battery needs charging. You don't need to remove the battery to charge. Instead, the battery has another wire for charging that you can connect the charging wire to. Ensure the rest of the robot is off. 
The battery can overcharge, so watch it when charging
More details can be found in Yahboom's pamphlet on the lab table 
