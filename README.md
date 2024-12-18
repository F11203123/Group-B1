# Introduction to Robotics - Group B1 2024

Members: 
- Gonzalo Diaz
- Mateo Ibieta
- Joaquin Roldan
- Leandro Volta


Overview:
- This documentation provides an overview of tasks relevant to operating and optimizing the Epson robotic arm.
- Design and model of a Four-wheel Drive Mecanum Mobile Robot for Surveillance Applications

## Indroduction to Robotics Tutorial
### Task 1: Pick and place

During this task the EPSON robot arm is set to pick three different tokens and three different blocks and place them in a tray.

  - Procedure:
    - STEP 1: Pick the token from the feeder
    - STEP 2: Align the token using the alignment feature
    - STEP 3: PLace the token in its corresponding place in the tray
    - Step 4: Follow the previous steps for the blocks


[Task1 code](CODES/task1.txt)

[Simulation](Simulations/simulations.md)



### Task 2: Token Stacking

During this task the EPSON robot arm is set to stack 10 tokens and 10 blocs on top of each other alternately.

  - Procedure
    - STEP 1: Pick a block from the feeder and place it in an specific point.
    - STEP 2: Pick a token a place it on top of the block
    - STEP 3: Repeat the process for the remaining pieces

[Task2 code](CODES/task2.txt)

[Simulation](Simulations/simulations.md)


### Task 3: Custom task
For this task, we set the Epson robot arm to pick and place a specif number of tokens in a desireble position using two counter system that reads the number of inputs and position variable to place the tokens. We focus on three main aspects:
  - Mechanical:
    - Design and 3D-printed an incline tray for six tokens with an angle of 15 degrees
    - Design and 3D-printed a token feeder that uses a piston as an actuator to move one token at a time.

    [Incline tray CAD](CAD-FILES/Inclined-tray.jpeg)
    [Token feeder CAD](CAD-FILES/Token-feeder.jpeg)

  - Electrical:
    - HMI design for the task and motion of the robot arm.
    - Wiring of the counter system and I/O box.

    [HMI manual mode](HMI/HMI-2.jpeg)
    [HMI auto mode](HMI/HMI-1.jpeg)
  - Programming:
    - Focus on the reading of inputs (number of times the buttons were pressed) to determine the number and positions of the tokens to pick and place. 

    [Task3 code](CODES/task3.txt)


### I/O BOX Configuration

The I/O Box configuration is an important tool while working with EPSON robot arms, therefore, the following configuration is set for every task of this course:

  - 🟢**GREEN BUTTON**: Start the program
  - 🔴**RED BUTTON** Emergency stop
  - 🔵**BLUE BUTTON**: Pause the program
  - ⚪️**WHITE BUTTON**: Resume program
  - 🟠**ORANGE BUTTON**: Go home


  [I/O BOX code](CODES/IO-BOX.txt) [I/O BOX diagram](CODES/IO-BOX.jpeg) 



## Introduction to Robotics - Final Project

This project explores the simulation of a four-wheel mecanum mobile robot using MATLAB's Mobile Robot Toolbox. Mecanum robots are valued for their omnidirectional movement, making them ideal for navigating complex environments. The focus is on designing a control system for path planning and collision avoidance, demonstrating the robot's versatility and potential in real-world applications.


# Objectives

The main objective of this project is to develop an autonomous Mecanum 4WD mobile robot specifically designed for surveillance in industrial environments, such as factories and warehouses where the range of vision of a common CCTV camera is blocked, thus, enhancing Industrial security with real-time communication.


# APPLICATIONS

  - Autonomous Industrial Surveillance.

  - Efficient Navigation in Confined Spaces.

  -  Real-Time Alerts and Reporting.

  - Cost-Effective Security Solution.

  - Adaptability for Broader Use Cases.

  - Environmental Safety Checks.

This ensures immediate detection and response to potential security threats, equipment malfunctions, or environmental anomalies, significantly improving the overall safety and security of industrial facilities during non-operational hours, reducing the need for human intervention and ensuring continuous monitoring.
 
 
# Robot design:
 The design of the robot is centered on the mecanum wheels, the suspension system and the camara base. Below you can find all the CAD drawings
    
[Robot design](FINAL-PROJECT/Mechanical)

Isometric view:


  ![alt text](image.png)

      

# Powertrain:
 Focuses on three main aspecs: motor requirenments, specifications and gearbox specifications.
  
 [Motor and Gear requirenment and specifications](FINAL-PROJECT/Powertrain)


# Suspension simulation:
 Uses matlab to simulate the robot's ability to mitigate the effects of the surface and loads using a suspension system.

 [Suspension system code and simulation](FINAL-PROJECT/Suspension)


# Navigation:
 The path and kinematics required for the robot to fullfill and adapt to real world environments depending on the specif job we want it to perform.

 [Navigation and kinematics](FINAL-PROJECT/Navigation)

[def]: image.png