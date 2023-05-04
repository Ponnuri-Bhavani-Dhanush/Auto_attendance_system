## Auto Attendance System
The Auto Attendance System is an IoT-based project that allows for the automatic tracking and recording of attendance. The system uses Arduino IDE, IR sensors, and an LED screen to detect the presence of individuals and record their attendance automatically. The IR sensor is placed at the entrance door, both in and out, to detect the movement of individuals. If a person enters, the in-sensor detects and adds a count increment, which is displayed on the LED screen. If a person exits, the system decrements the count by one and displays the updated count on the screen.

## Dependencies
- Arduino IDE
- IR sensors
- LED screen
- Breadboard
- Jumper wires
- 10kΩ resistor

## Circuit Diagram
![image](https://user-images.githubusercontent.com/111173151/236218800-d68292f9-8bed-48ef-86d2-79e8e1fa6781.png)


## Installation
1. Download the Arduino IDE software from the official website.
2. Connect the IR sensor and LED screen to the Arduino board using the breadboard and jumper wires.
3. Open the Arduino IDE software and upload the code provided in the project repository.
4. Connect the power source to the Arduino board.

## Usage
1. Turn on the power source.
2. The LED screen will display the initial attendance count as zero.
3. When a person enters the room, the in-sensor will detect the movement and add one to the attendance count, which will be displayed on the screen.
4. When a person exits the room, the out-sensor will detect the movement and subtract one from the attendance count, which will be displayed on the screen.
