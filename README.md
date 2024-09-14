# Arduino Obstacle Avoiding Robot
## Problem Statement
In an increasingly automated world, obstacle avoidance is a critical aspect of robotics. Robots operating autonomously need to navigate through complex environments while avoiding obstacles. This project aims to develop an Arduino-based obstacle avoiding robot capable of detecting and circumventing objects in its path using sensors, motors, and a servo-controlled ultrasonic sensor system.

## Why This Project?
The goal of this project is to understand and implement the fundamental principles of autonomous navigation using inexpensive and widely available components. Building an obstacle-avoiding robot allows us to explore real-world applications of embedded systems, robotics, and sensor integration. This project enhances our understanding of automation, motor control, sensor data processing, and decision-making algorithms, all of which are essential for developing more complex robotics systems.

## Components Used
Arduino Uno
L298N Motor Driver
Ultrasonic Sensor (HC-SR04)
DC Motors with wheels
Servo Motor (for rotating the ultrasonic sensor)
Breadboard and Jumper Wires
9V Battery

## Procedure

1. Component Assembly:
Connect two DC motors to the motor driver to control the left and right wheels.
Attach the ultrasonic sensor to a servo motor to allow rotation and scanning of the environment.
Power the Arduino and motors using a 9V battery.

2. Programming:
Write code to control the movement of the robot and make decisions based on the input from the ultrasonic sensor.
Use the ultrasonic sensor to measure the distance between the robot and potential obstacles. If an obstacle is detected within a threshold distance, the robot calculates a new path to avoid it.

3. Testing and Calibration:
Test the robot by placing obstacles in its path and observe its ability to avoid them.
Fine-tune the motor speeds, sensor reading threshold, and servo movement to achieve smooth obstacle avoidance.

## Benefits
1. Hands-on Learning: This project offers practical knowledge of robotic motion, motor control, and sensor integration.
2. Automation: Enables autonomous navigation, which is essential in robotics applications such as automated vacuum cleaners, drones, and autonomous vehicles.

## Skill Development:
Develops problem-solving, coding, and hardware integration skills, as well as experience working with embedded systems.
