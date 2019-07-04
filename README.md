# Maze-Solving-Bot
This robot goes throughout the maze and records the decision made by it to reach the end of the maze (displays the path of the maze).\
The robot uses "Left hand rule" (prefers to turn left when given a choice between left, straight, right turn).
# Sub-Systems
This robot typically consists of 3 main subsystems.\
**1.Drive System**\
      Consists of the chassis, set of mmotors and wheels. The chassis is small enough to navigate through the maze.\
**2.Array Of Sensors**\
      The sensors read the data - the current state of the surrounding meaning the path of the maze to the ATmega16(micro-controller). These are usually infra-red sensors which pick up light reflected light of the track.\
**3.Control System**\
      The control system is circuit boards which function as the brain of the robot. The Control system runs a "Maze Solving Algorithm" based on the information recieved by the board from the sensors.
