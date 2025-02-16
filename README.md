# Human Following Robot

This project involves building a human-following robot using an Arduino UNO, ultrasonic sensor, IR sensors, and a motor shield. The robot detects and follows moving objects, such as a human hand, by processing data from the sensors and controlling its motors accordingly.

## Table of Contents

- [Introduction](#introduction)
- [Components Required](#components-required)
- [Circuit Diagram](#circuit-diagram)
- [Assembly Instructions](#assembly-instructions)
- [How It Works](#how-it-works)
- [Demonstration Video](#demonstration-video)

## Introduction

The Human Following Robot is designed to detect and follow a moving object using a combination of ultrasonic and infrared (IR) sensors. The ultrasonic sensor measures the distance to an object, while the IR sensors detect motion. Based on the sensor inputs, the Arduino controls the motors to move the robot in the direction of the detected object.

## Components Required

- Arduino UNO
- Motor Shield
- Ultrasonic Sensor (HC-SR04)
- Two IR Sensors
- Micro Servo Motor (SG90)
- Four Dual Shaft BO Motors with Wheels
- Chassis or Frame Material (e.g., plastic board, cardboard, plexiglass, or MDF board)
- Jumper Wires
- Power Source (e.g., two lithium-ion batteries)

## Circuit Diagram

![Human Following Robot Circuit Diagram](https://letsmakeprojects.com/wp-content/uploads/2021/03/human-following-robot-circuit-diagram.jpg)

## Assembly Instructions

1. **Frame Construction:**
   - Cut a square piece of plastic (or alternative material) to serve as the base frame.
   - Attach the four BO motors to the corners of the frame using hot glue or double-sided tape.
   - Fix the wheels onto the motor shafts.

2. **Mounting Electronics:**
   - Secure the Arduino UNO at the center of the frame.
   - Attach the motor shield on top of the Arduino.
   - Mount the micro servo motor at the front of the robot and attach a small stick to its shaft.
   - Create a small case for the ultrasonic sensor and mount it on the servo motor.
   - Position the IR sensors on either side of the ultrasonic sensor.

3. **Wiring Connections:**
   - Connect the motors to the motor shield as per the circuit diagram.
   - Wire the ultrasonic sensor and IR sensors to the appropriate pins on the Arduino.
   - Ensure all connections are secure and insulated to prevent short circuits.

## How It Works

### Object Detection:
- The ultrasonic sensor continuously measures the distance to objects in front of the robot.
- IR sensors detect the presence and position of the object (left or right).

### Movement Control:
- Based on sensor inputs, the Arduino determines the direction of the object.
- The robot moves forward, left, or right to follow the object.
- If no object is detected within the specified range, the robot stops.

### Servo Operation:
- The servo motor rotates the sensor assembly to scan for objects, allowing the robot to detect and follow objects within a wider field of view.

## Demonstration Video

For a visual demonstration of the Human Following Robot in action, watch the following video:

[![Watch the video](https://img.youtube.com/vi/bdQL5vsal_M/0.jpg)](https://youtu.be/bdQL5vsal_M)

