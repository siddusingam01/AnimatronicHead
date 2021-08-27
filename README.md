# AnimatronicHead
## About the Project :
This is a project where a Humanoid robot head is built with various functionalities as that of a human.
They include jaw movement in synchronism with voice, eye movement, eye lid movement and head
movement. This whole system includes the use of different hardware and software components.
Controllers such as Raspberry pi are put into use for movement of physical components. Speech of the
system is governed by a Python program which would be in interactive mode. The user can speak to the
system as if he speaks to a human. This software functionality is implemented in Raspberry pi. The
synchronism of this voice with the jaw movement is also achieved in software basis, where
Multithreading is involved. Two threads one controlling the jaw movement and the other controlling the
voice flow would be running simultaneously. These on a whole would give a whole experience of
speaking to human which is actually a machine. Eye movement, eyelid movement and head movement
will be controlled using servo motors. Parts such as eyes, eyelids will be fabricated using 3D printing.

## Introduction : 
We tried to implement few characteristics int o humanoid head like eye movement (which involves
rotation of eye balls and movement of eye lashes), jaw movement (this movement is initiated whenever
we like to communicate with other.), neck movement (the neck is rotated to the direction where the
sound is heard just like a human) and a communication mechanism. All these functions are synchronised
to make it more like a human.
For our first implementation of eye rotation and movement in eye lashes, we connected 4 servo motors
(2 for each eye) which are operated using raspberry pi. Even for jaw movement and neck rotation we 
have used servo motors in the same manner. Our neck rotation is initiated to move in that particular
direction unlike eye movement whenever a sound or noise is detected by the sound sensors. Our jaw
movement is initiated whenever it is trying to communicate or to give response. The sound card
connected to the raspberry pi gets our query and then it is converted to text or our view. We have
implemented a machine learning chat bot from which it fetches the answer and replies along with jaw
movement using a microphone.

### Built With :
The following are the major components and technical aspects put into use in this Project :
- 3D Designed components.
- Servo
- Rapberry Pi
- Sound Sensor and Sound Detection Module Arduino 
- TowerPro Mg996R
- USB Microphone

## Getting Started :

### Preperation and Pre Installations :
- Have your components printed from a reliabel 3D printing service. Better to have double coating with any material used. Your components would be delicate, so better handle with care.
- Intall Raspbian OS into the Raspberry pi.
- Install Python interpreter into Rapberry pi (We have used Thonny)
- Cast you Pi screen onto a desktop using the HDMI cable or Wireless Connection

### Working :
- Fix the Jaw in the following way,
 
![image](https://user-images.githubusercontent.com/69643168/131075620-7b7724be-2625-4d33-81f8-a597a3360f58.png)

- Fix the Eye Holders shown in the following way,

