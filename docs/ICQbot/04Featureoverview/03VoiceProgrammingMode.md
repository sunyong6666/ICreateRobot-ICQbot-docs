# Voice Programming Mode

## Voice Direct Control  

### **<font style="color:rgb(42, 43, 46);">Demonstration</font>**
![](img/VoiceProgrammingMode01.gif)

### How to control the motor's movement using voice commands?  
Steps:  

1. Preparation  

| ![](img/VoiceProgrammingMode02.png) | ![](img/VoiceProgrammingMode03.png) | ![](img/VoiceProgrammingMode04.png) |
| :---: | :---: | :---: |
| ICQbot Xiao Q Robot × 1 | Voice Recognition Sensor ×1 | Motor × 1 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|


1. Steps Display

| ![](img/VoiceProgrammingMode05.gif) | ![](img/VoiceProgrammingMode06.gif) |
| --- | --- |
| 1、Press and hold the power button on the Xiao Q Robot for 3s to power it on.   | 2、Connect the motor to Port 1 (green side).   |
| ![](img/VoiceProgrammingMode07.gif) | ![](img/VoiceProgrammingMode08.gif) |
| 3、Connect the voice sensor to Port 1 (blue side).   | 4、Wake up the voice recognition sensor by saying "Hello Xiao Q" and wait for the response.  <br/> Say “Motor 1 forward” to rotate the motor. The system will reply, <br/>“Motor 1 forward recognized,” and the motor will rotate. <br/>Say “Stop” to stop the motor.   |


**Note:**  
The voice command should match the motor's port, as shown below:  

|  Port Connection   |  Command Word<br/> (Motor 1 Forward)   |  Command Word <br/>(Motor 2 Forward)   |
| :---: | :---: | :---: |
|  Port 1 connected to motor   |  Motor rotates   |  Motor does not rotate   |
|  Port 2 connected to motor   |  Motor does not rotate   |  Motor rotates   |
|  Both Port 1 and Port 2 connected to motors   |  Both motors rotate   |  Motor rotates   |


*Other command word effects can be tried on your own. 

---

## Voice Programming Control  
### **<font style="color:rgb(42, 43, 46);">Demonstration</font>**
![](img/VoiceProgrammingMode09.gif)

### How to use voice programming to control the robot's movement?  
1. Preparation

| ![](img/VoiceProgrammingMode10.png) | ![](img/VoiceProgrammingMode11.png) | ![](img/VoiceProgrammingMode12.png) |
| :---: | :---: | :---: |
| ICQbot Xiao Q Robot × 1 | Voice Recognition Sensor ×1 | Motors × 2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |


2. Structure Setup  

| ![](img/VoiceProgrammingMode13.png) | ![](img/VoiceProgrammingMode14.png) | ![](img/VoiceProgrammingMode15.png) | ![](img/VoiceProgrammingMode16.png) |
| :---: | :---: | :---: | :---: |
| Step 1 | Step 2 | Step 3 | Step 4 |
| ![](img/VoiceProgrammingMode17.png) | ![](img/VoiceProgrammingMode18.png) | ![](img/VoiceProgrammingMode19.png) | ![](img/VoiceProgrammingMode20.png) |
| Step 5 | Step 6 | Step 7 | Step 8 |
| ![](img/VoiceProgrammingMode21.png) | ![](img/VoiceProgrammingMode22.png) | ![](img/VoiceProgrammingMode23.png) | ![](img/VoiceProgrammingMode24.png) |
| Step 9 | Step 10 | Step 11 | Step 12 |
| ![](img/VoiceProgrammingMode25.png) | ![](img/VoiceProgrammingMode26.png) | ![](img/VoiceProgrammingMode27.png) | ![](img/VoiceProgrammingMode28.png) |
| Step 13 | Step 14 | Step 15 | Step 16 |
| ![](img/VoiceProgrammingMode29.png) | ![](img/VoiceProgrammingMode30.png) |  |  |
| Step 17 | Step 18 |  |  |


3. **<font style="color:rgb(42, 43, 46);">Demonstration</font>**

![](img/VoiceProgrammingMode31.gif)

4. Steps Display

| ![](img/VoiceProgrammingMode32.gif) | ![](img/VoiceProgrammingMode33.gif) |
| --- | --- |
| 1、Press and hold the power button on the Xiao Q Robot for 3s to power it on.<br/>   Connect the motor modules to Ports 1 and 2 (green side).   | 2、Connect the voice recognition sensor to Port 1 (blue side).   |
| ![](img/VoiceProgrammingMode34.gif) | ![](img/VoiceProgrammingMode35.png) |
| 3、Wake up the voice recognition sensor by saying "Hello Xiao Q" and <br/>wait for the response.   Say the command: “Start programming”, <br/>“Turn left”, “Wait for 1 second”, “Stop”, and “End programming.”<br/>   Say “Execute program” for the motors to perform the corresponding actions.   | Attached: Detection diagram of the voice recognition sensor. |


*Other command word effects can be tried on your own. [Click here to learn more command words.  ](#aEc3E)

## Voice Command List
| Type | Commands | Responses |
| :---: | :---: | :---: |
| wake-up phrase | Hello,Xiao Q | Xiao Q is here |
| Motion commands | Move forward | Move forward recognized |
| Motion commands| Move backward | Move backward recognized |
| Motion commands | Turn left | Turn left recognized |
| Motion commands | Turn right | Turn right recognized |
| Motion commands| Stop movement | Stop movement recognized |
| Motor commands | Motor 1 run forward | Motor 1 run forward recognized |
| Motor commands | Motor 1 run backward | Motor 1 run backward recognized |
| Motor commands | Motor 1 stop | Motor 1 stop recognized |
| Motor commands | Motor 2 run forward | Motor 2 run forward recognized |
| Motor commands | Motor 2 run backward | Motor 2 run backward recognized |
| Motor commands | Motor 2 stop | Motor 2 stop recognized |
| Waiting commands | Wait for one second | Wait for one second recognized |
| Waiting commands | Wait for two seconds | Wait for two seconds recognized |
| Waiting commands | Wait for three seconds | Wait for three seconds recognized |
| Waiting commands | Wait for ten seconds | Wait for ten seconds recognized |
| Waiting commands | Wait for twenty seconds | Wait for twenty seconds recognized |
| Waiting commands | Wait for thirty seconds | Wait for thirty seconds recognized |
| Waiting commands | Wait for tilting | Wait for tilting recognized |
| Waiting commands | Wait for shaking | Wait for shaking recognized |
| Waiting commands | Wait for approching | Wait for approching recognized |
| Waiting commands | Wait for button 1 press | Wait for button 1 press recognized |
| Waiting commands | Wait for button 2 press | Wait for button 2 press recognized |
| Light commands | Turn on the light | Turn on the light recognized |
| Light commands | Turn off the light | Turn off the light recognized |
| Light commands | Red light | Red light recognized |
| Light commands | Yellow light | Yellow light recognized |
| Light commands | Green light | Green light recognized |
| Light commands | Blue light | Blue light recognized |
| program start / finish command | Start programing | Start programing recognized |
| program start / finish command | Finish programing | Finish programing recognized |
| program run / stop commands | Run the program | Run the program recognized |
| program run / stop commands | Stop the program | Stop the program recognized |
| program modify commands | delete last step |  |
| ICQbot programming Words | Move left  | Move left recognized |
| ICQbot programming Words | Move right | Move right recognized |
| ICQbot programming Words | Move up | Move up recognized |
| ICQbot programming Words | Move down | Move down recognized |
| ICQbot programming Words | Jump | Jump recognized |
| ICQbot programming Words | Go home | Go home recognized |
| ICQbot programming Words | Stop | Stop recognized |


