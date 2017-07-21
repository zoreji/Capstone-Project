# 3-axis Self-Stablizing Camera Mount

## Abstract
A camera mount that uses gyroscopes and accelerometers to self-stabilize from any rotational movement along the 3-axes. Parts consist of the mount, three Hitec HS-485HB analog servos, LSM6DS3 IMU Board, which housed the accelerometers and gyroscopes, and an Arduino Mega 2560 microcontroller. Each part of the mount was constructed with the MakerBot Replicator. Then it was assemble where the three servos are stack on top of each other, from bottom to top, Yaw, Roll and Pitch. The data gathered from the sensor, sends data toward the Arduino Mega 2560 Microcontroller. From the Arduino, it uses the data to calculate forces and change of angle from the sensor where it translate it to analog volt for the servos.

## 1.0 Introduction

As technology grows in today, mimicking human movements become more prevalent with human and technology interaction. One of the ways to mimic human movement is using accelerometers and gyroscope. These sensor can help track rotational movement of a human and translate into data where companies like Oculus and HTC can create the latest VR technologies. The purpose of this report is to walk through the process of designing and building a 3-axes camera mount with accelerometers and gyroscope to self-correct any human rotational movement along the 3-axes. The report will demonstrate the designing and building the prototype, our finding and problem that arise, and how did we solve these problems. Overall this report will reveal the application of a 3-axes camera mount in today market and the future it could hold when implemented correctly.

## 2.0 Overview

The 3-axes self-stabilizing camera mount uses two essential sensors. An accelerometer, which gather data of force applying to the sensor, and a gyroscope, a sensor that reads the change of angle applying to the sensor. Once the sensor gather the data, they send it to the Arduino board which calculate the data and translate the code into analog output where 3 servos, each mounted on different axes, position itself to those coordinates. This technology is used in Military, for plane and ships, the smart phone industry, space exploration and the robotics industry.

### 2.1

The concept of using gyroscopes as a way to stabilize an object on an unleveled surface dates back to Ancient Greek, Chinese and Romans. Where they try to stabilize objects on ship to traverse across seas. It was not until the early 19th Centuries where scientist develop tools and reduce the amount of variables for traveling through choppy or fog seas. A French scientist name Fleuriais created the first gyroscope by a top that was continuously blow by air jets which maintain the top stability. By the 1898, Austrian Ludwig Obry patented a gyroscopic inertia which is the base to all modern gyroscope.

## 3.0 Process

### 3.1 Design

My partner, Gabriel Natividad, and I discus ideas of designing the structure and the location of each motor. We debated on several design of the prototype. One design was L shape bracket similar to the camera mount used in the film industry, but the problem was the size and weight of the camera mount. So we discover a design where each of the motor were stack on top of each other. This design make so that the weight is more center on the middle where the camera is rather the motor orbiting around the camera. The feature that was to be implemented were, portability, a tracking capability, and manual control over the camera mount.
```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/zoreji/Capstone-Project/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
