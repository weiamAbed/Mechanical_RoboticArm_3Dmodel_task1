# Robotic Arm 3Dmodel
This repository is for task 1 of mechanical track of my summer training at Smart-Methods.
I have contained the robotic arm after placing it's individual parts in their appropiate positions. Incoming, are the steps I got through to have this final result.
-----------------------------------------------------------------------------------------------------------------------------------------
After downloading the individaual parts from Smart-Methods GitHub account, and since i'm using MAYA software, it does not support .stl extension, so to convert it to .obj ( which is supported by MAYA ) I used "https://www.meshconvert.com/" website for converting.
Next I import all of the parts and unified the sizes beacause some parts were smaller than others.
And after I'm done with placing the parts, I (combined) all the parts togrther to have a single prop. 
Finally,I had to turn it back to .stl to be able to upload it in my GitHub account so I export them as a .obj (not the MAYA default which is .mb) and again used the MeshConverter website.
NOTE:: 
- the final position of the model I decided to go with was NOT the initial position of the robot, since different links and joints are much visible and understandable by this position.
- I added a motors in each joint (including a motor for the base which is inside the base body at the botton) and a smaller different motor than the rest at the gripper.
-----------------------------------------------------------------------------------------------------------------------------------------
INSTRUCTIONS OF THE INSTALLATION OF THE ROBOTIC ARM:
- 1- At the begining, the robotic arm consists of 5 parts: base, waist, 2 links and a gripper. In addition of 5 motors.
- 2- Place the base on a flat surface
- 3- Then put the second part which is the waist on top of the base.
- 4- Next place the first link jointing with the base, and the second link jointing with the first link .
- 5- Now for the gripper, place it at the end of the second link. 
- 6- Finally, the motors are placed at the joints including the one inside the body, and the one controlling the gripper (notice that this motor is sligthly smaller than the rest ).
