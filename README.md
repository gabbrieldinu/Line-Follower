# Line-Follower

Made by Dinu Gabriel and Neacsu VLad

Coordinated by Andrei Dumitriu

# Project Explanation

  The project consists of creating a simple line follower using the laboratory kit. It that has to finish a track made by the proffessor and ensure that it does so in the least time possible. With the code attached, our line follower managed to finish the track in 18.2 seconds, securing the highest mark ( given only to times under 20 seconds). There is also a video attached to see it in action.

# Explanation of the main functions in the code:
  
  The setup() function sets up the sensors and pins and at the end there is a while loop that is used to calibrate the sensors. It works by reading the values of the edge sensors ( left and right) and moving accordingly. The simplest way to describe it is as follows: if the left sensor value is lower than 700 ( it sees black) move to the left ( by activating the right motor) until the value is reaches 700 and then do the same for the opposite sensor and back and forth 10 times.

  The pidControl() function, which reads the error ( the amount of white the sensor sees) and modifies motors based on given values so that the error is minimized. 
  
  The setMotorSpeed() function maps given values to library specific values ( 0-255) and inputs current into the motor based on the value.

# Components:

  - Arduino Uno
  - QTR-8A reflectance sensor, along with screws
  - Breadboard - medium (400pts)
  - L293D motor driver
  - 2 DC motors 
  - Power source ( 7.4V LiPo battery )
  - 2 Wheels ( only backside )
  - Wires
  - Ball caster
  - Chassis


# Link to video: https://www.youtube.com/watch?v=_huuC-UTbUY

# Images of setup:

![Alt text](https://user-images.githubusercontent.com/74376628/213796434-d18bd075-9f12-40b8-81d1-e2bbab730b76.jpg)

![Alt text](https://user-images.githubusercontent.com/74376628/213796475-07977c8c-8b06-47af-b9d6-3bc93ad8bf26.jpg)



