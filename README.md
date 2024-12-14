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


[I/O BOX code](CODES/IO-BOX.txt)