# Camera Gimbal
My project is an automatic camera stabilizer. An accelerometer measures rotation on axes and controls servo motors to offset the rotation.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| James Tsaggaris | Archbishop Mitty High School | Computer Science, Mechanical Enginerring | Incoming Sophomore

![Headstone Image](https://lh3.googleusercontent.com/pw/AM-JKLXkiG5YJ6zjkGtchbxGNRkhMWTsvNOYVN7F4_TMeJu3X0Uwqnjes68TNkxVbRD-3skI3QnJhD4HCk5AlsjqnLztQqVedHypB-GSGs5B76UMmsL-jV-JVgt28HpZHxOLngdh5_rUgFyUb7_sYTPO09Y=s1430-no?authuser=0)
  
# Final Milestone

[![Final Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1612573869/video_to_markdown/images/youtube--F7M7imOVGug-c05b58ac6eb4c4700831b2b3070cd403.jpg )](https://www.youtube.com/watch?v=F7M7imOVGug&feature=emb_logo "Final Milestone")

# Second Milestone

**Camera Holder**

![Image](https://i.postimg.cc/DzQdvJR2/Screen-Shot-2022-07-07-at-4-02-38-PM.png)
![Image](https://i.postimg.cc/j5ZHNVsm/Screen-Shot-2022-07-07-at-4-03-26-PM.png)

[![Third Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1612574014/video_to_markdown/images/youtube--y3VAmNlER5Y-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=y3VAmNlER5Y&feature=emb_logo "Second Milestone")

# First Milestone

The main components include 1 Arduino nano, 1 MPU6050 accelerometer, and 2 servo motors. I connected these components on a breadboard with wires.

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
- servos #1 and #2 power and ground to 5V rail and ground rail

**Arduino**

An Arduino is a programmable circuit board. The specific model I use is an Arduino Nano, the smallest of all Arduinos. The Arduino has digital and analog pins that either input or ouptut. Digital signals are either HIGH or LOW, while analog pins give values in a range. The Arduino also has a 5V power and a ground pin, which I connect to the respective breadboard rails.

**MPU6050**

The MPU6050 accelerometer measures acceleration. A suspended mass on springs moves when there is acceleration. This causes a change in capacitance, which is proportional to the acceleration on the axis.

![image](https://hackster.imgix.net/uploads/attachments/1273992/MEMS-Accelerometer-Working.gif?auto=compress&gifq=35&w=1280&h=960&fit=max)

**Servo motor**

Servo motors are motors that can be set to precise angles, from 0 to 180 degrees. This allows me to set them to the opposite angle measured by the MPU6050.

**Circuit Diagram**

![Image](https://i.postimg.cc/jjjgFhLp/circuit.png)

[![First Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1612574117/video_to_markdown/images/youtube--CaCazFBhYKs-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=CaCazFBhYKs "First Milestone")

# Starter Project

My starter project is a customizable Arduino project. more detail
