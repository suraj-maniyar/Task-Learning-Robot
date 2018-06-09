
Main_Project:
An interactive User-Interface to control and train the robotic arm using encoder readings or vision. It streams the encoder readings from the 
myRio to the PC during each step of the task and again uses these values streamed from computer to the myRio to perform the same task desired 
number of times.


vision_myrio:
It uses the live feed from camera to track an object of a particular colour.


Reader and writer:
This VI streams the data from myRio to the host computer during the process of task learning and again from the computer to the myRio while 
autonomously performing the task.Note that this VI must be running initially before the Main Project VI is deployed on the myRio.