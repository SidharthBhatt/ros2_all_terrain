This is a NSF Iot4AG REU Project 

Background: 

One of the goals of the OAT's center is to have a fully automated farm system with a tractor, drones, ground sensors, etc all speaking together. In order to facilitate this, they all need to communicate together. The current plan is to use ROS, which is a popular robotics library. Before coding the tractor, we are planning to use the mini robot as a testbed to explore ROS. We want to be able to scan our surroundings, pathfind, and complete complex tasks using the robot. We plan to create demos that showcase the robot's functionality. Then once we understand how to do that, we can move onto the Polaris Ranger. So far, I have tried to emulate the robot in simulation, constructed the robot, become familiar with its code, created a repository, and I am in the process of making it move with code. One of the example demos we want to complete is making the robot scan the lab area, and go from one side to the other.

Video on How to Charge the Robot & Turn it On: 

https://youtube.com/shorts/ynTDrik55YA
- robot located in the ABE 3070 UAV lab
- find the power cable and plug it into the black connector
- the battery can be charging and also supply power to robot at same time (has two outputs)
- however don't charge while using 
- use the right side switch to turn it on and off

Steps to Connect to the Robot: 

1. Ensure the robot is on by switching all switches on 
2. Wait 2-3 minutes for the robot to boot up 
3. connect to the OATScenter wifi (passsword on the whiteboard on right side) 
4. SSH into the robot using its IP displayed on the small screen (ssh jetson@192.168.100.53) 


Tasks 
- Redo the upload of the code from the robot's directory onto github. The one currently up doesn't have all the directories. When you need access to the github repo, ping me on slack, and i'll add you ASAP
- Watch the yahboom tutorial videos and run their code to make the robot move 
- Create a new development directory for our code
  - Use their code to create a demonstration video and code on how to make the robot move in the development directory
  - Show lines of code that can make it move in x, y, xy directions for a specified distance 
  - Use their code to create a demonstration video and code on how to use the lidar to detect their surroundings
  - Use their code to create a demonstration video and code on how to pathfind around the lab 
    given a point in the lab, generate a path, avoid obstacles, and know where it is in the lab (localization) and reach the destination

Other Details: 

- Do NOT under any circumstances charge the battery and use the robot at the same time. (we have been warned the battery may explode)
- If the robot starts beeping after you turn on, the battery needs charging. You don't need to remove the battery to charge. Instead, the battery has another wire for charging that you can connect the charging wire to. Ensure the rest of the robot is off.
- The battery can overcharge, so watch it when charging
- More details can be found in Yahboom's pamphlet on the lab table 
