# Camera Gimbal
My project is an automatic camera stabilizer. An accelerometer measures rotation on axes and controls servo motors to offset the rotation.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| James Tsaggaris | Archbishop Mitty High School | Computer Science, Mechanical Enginerring | Incoming Sophomore

![Headstone Image](https://lh3.googleusercontent.com/pw/AM-JKLXkiG5YJ6zjkGtchbxGNRkhMWTsvNOYVN7F4_TMeJu3X0Uwqnjes68TNkxVbRD-3skI3QnJhD4HCk5AlsjqnLztQqVedHypB-GSGs5B76UMmsL-jV-JVgt28HpZHxOLngdh5_rUgFyUb7_sYTPO09Y=s1430-no?authuser=0)

# Final Milestone

**Camera Holder CAD**

In this milestone, I created a CAD camera holder in Shapr3D. 

<img src="https://i.postimg.cc/DzQdvJR2/Screen-Shot-2022-07-07-at-4-02-38-PM.png" width="547" height="384"> <img src="https://i.postimg.cc/j5ZHNVsm/Screen-Shot-2022-07-07-at-4-03-26-PM.png" width="318" height="384">

[![Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1612573869/video_to_markdown/images/youtube--F7M7imOVGug-c05b58ac6eb4c4700831b2b3070cd403.jpg )](https://www.youtube.com/watch?v=F7M7imOVGug&feature=emb_logo "Final Milestone")

# Second Milestone

[![Milestone](https://i3.ytimg.com/vi/kxWnwhuL-DE/maxresdefault.jpg)](https://www.youtube.com/watch?v=kxWnwhuL-DE "Second Milestone")

In this milestone, I created code for the Arduino. I installed the libraries I2Cdev and MPU6050_6Axis_MotionApps20. Then, I initiated the two servo motors and attached them to D10 and D11 pins. After getting analog data from the MPU6050, an issue I encountered was that the MPU6050 was not calibrated. I had to download code to calibrate the XYZ gyro and accelerometer offsets. I used a function from the MPU6050 library to convert the quaternion to angles. Then, I set servo 1 to the pitch times -1 and servo 2 to the roll. I learned that pitch is rotation in the side to side axis, roll is rotation in the front to back axis, and yaw is rotation in the vertical axis.

# First Milestone

[![First Milestone](https://i3.ytimg.com/vi/kxWnwhuL-DE/maxresdefault.jpg)](https://www.youtube.com/watch?v=6pxER5YcX_w "First Milestone")

The main components include 1 Arduino nano, 1 MPU6050 accelerometer, and 2 servo motors. In this milestone, I connected these parts on a breadboard with wires.

**Connections**

- Arduino 5V to 5V rail
- Arduino GND to ground rail
- Arduino A4 to MPU6050 SDA
- Arduino A5 to MPU6050 SCL
- Arduino D10 to servo #1
- Arduino D11 to servo #2
- MPU6050 VCC to 5V rail
- MPU6050 GND to ground rail
- MPU6050 SCL to 10kΩ resistor to 5V rail
- MPU6050 SDA to 10kΩ resistor to 5V rail
- MPU6050 ADO to ground rail
- servos #1 and #2 power to 5V rail, ground to ground rail

**Arduino**

An Arduino is a programmable circuit board. The specific model I use is an Arduino Nano, the smallest of all models. The Arduino has digital and analog pins that either input or ouptut. Digital signals are either HIGH or LOW, while analog pins give values in a range. The Arduino also has a 5V power and a ground pin, which I connect to the respective breadboard rails.

**MPU6050**

The MPU6050 accelerometer measures acceleration. A suspended mass on springs moves when there is acceleration. This causes a change in capacitance, which is proportional to the acceleration on the axis.

<img src="https://hackster.imgix.net/uploads/attachments/1273992/MEMS-Accelerometer-Working.gif" width="640" height="480">

**Servo motor**

Servo motors are motors that can be set to precise angles, from 0 to 180 degrees. This allows me to set them to the opposite angle measured by the MPU6050.

**Circuit Diagram**

<img src="https://i.postimg.cc/jjjgFhLp/circuit.png" width="360" height="660">

# Starter Project

My starter project is a customizable Arduino project. It includes a pressure sensor, an Arduino, and a servo motor. I take input from the pressure sensor and input it to the Arduino. Then, my code maps the pressure readings (from 0 to 1023) to the range of the servo motor in degrees (0-180). Finally, it sends a digital signal to the servo motor to control its angle. In this project, I learned how to solder, connect pins with wires, and create Arduino code.
