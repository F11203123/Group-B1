# Introduction to Robotics Tutorial- Group B1 2024

Members: 
- Gonzalo Diaz
- Mateo Ibieta
- Joaquin Roldan
- Leandro Volta


Overview:
- This documentation provides an overview of tasks relevant to operating and optimizing the Epson robotic arm.


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


### Task 3: Project

### I/O BOX Configuration

The I/O Box configuration is an important tool while working with EPSON robot arms, therefore, the following configuration is set for every task of this course:

  - 🟢**GREEN BUTTON**: Start the program
  - 🔴**RED BUTTON** Emergency stop
  - 🔵**BLUE BUTTON**: Pause the program
  - ⚪️**WHITE BUTTON**: Resume program
  - 🟠**ORANGE BUTTON**: Go home


[I/O BOX code](CODES/IO-BOX.txt)