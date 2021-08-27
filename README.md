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
- Sound Sensor and Sound Detection Module Arduino X 4
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

![image](https://user-images.githubusercontent.com/69643168/131082432-d27b56c0-1a6a-4073-be7b-3175cf19c58a.png)


![image](https://user-images.githubusercontent.com/69643168/131082500-0848f29f-016a-4e6d-8140-1fc2d41e3545.png)


![image](https://user-images.githubusercontent.com/69643168/131075961-cd1c53fb-f91f-4382-8562-be9bb51980ab.png)


![image](https://user-images.githubusercontent.com/69643168/131075865-c8e2be62-d25c-4431-b8cc-b8db6199f6bd.png)


![image](https://user-images.githubusercontent.com/69643168/131075746-8ea3d2fc-0c29-408d-9f86-883c43091f89.png)


- Mount the Discrete Eye parts one apon the another


![image](https://user-images.githubusercontent.com/69643168/131075914-797b74f8-e2d7-42ed-94ff-13a0170092fb.png)


![image](https://user-images.githubusercontent.com/69643168/131076002-b1fae155-50cc-4cdb-af6d-5e7f2b59fb88.png)


- Fix the eyes in the Frame and the eye frame would look like the following way, 

![image](https://user-images.githubusercontent.com/69643168/131082576-e1fedf11-fe4a-4a3f-bf9f-f9781cbdb50b.png)


![image](https://user-images.githubusercontent.com/69643168/131076077-1ae5eeb6-c9b5-483e-9aa9-63a43009d5cf.png)


- Fix the Eye Frame and the Jaw frame to the face

- Now arrange the next servo in the socket provided

- Connect the sound sensors to the face and place them at the front part such that each of them is at 45 degree angular distance to each other and all of them combinedly cover 180 degrees

- Connect and place the USB Mircophone at the front part of the face, preferably at the center

- Place the intents.json, trainbot, chatgui, classes, words files in the same directory.

- Make changes in the intents.json file as per your requirements of the chatbot, but remember the format of inserting before you do that.

- Now, run the train chatbot code and the chatgui code. 
