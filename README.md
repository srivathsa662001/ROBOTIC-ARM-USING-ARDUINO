 ROBOTIC-ARM-USING-ARDUINO
The system uses an Arduino UNO board that controls the movement robotic arm through Servo motors .
TABLE OF COMPONENTS FOR IMPLEMENTATION OF   ROROBOTIC ARM USING ARDUINO
Sl.no	Components Used 	Quantity
1.	Arduino Uno	1
2.	SG90 Servo Motor	4
3.	HC-05 Bluetooth Module	1
4.	Robotic Arm	1
5.	Connecting Wires	-
6.	12-volt Battery	1
7.	Android Device with custom application installed	1

Procedure for implementation of Robotic Arm
1)	Install Arduino.Ide application from Arduino CC official website.
    Once the application is installed, click on the icon   and open the application

2)	Once the application opens, the following screen appears. Go to File and select New to ensure that new file is opened and previous files are closed.

3)	Type the program code on the text editor. Use proper comments while typing for future upgradation if required. Also check for angle settings for Servo motors.
 
4)	Save the program. Choose the folder so that all the related file information and documents can be stored at one location. Create folder named ARM_Project in Local Disk D and store the code file there.
 
5)	Once the file is stored, click Tools, select Board: click on Arduino AVR Boards and select Arduino Uno.

6)	Click on Tools, select Port and click Select COM3(Arduino Uno)
7)	
Note: COM port settings may vary depending on USB port being used. In that case COM port has to checked by opening Control Panel select Hardware And Sound, click Devices and Printers, select Check the COM port on Unspecified Devices List.
 
7)	Click on Sketch, select Verify/Compile. Check for Syntax Errors and Runtime Errors. Make necessary change. 

8)	Connect the Circui    

9)	Click Sketch and select Upload. The former part of Step 8 can be ignored and we can directly proceed with the latter part of Step 8.

10)	If there are no errors in the code,  we get “Done Uploading” message on Terminal Window present on the bottom side the Editor window.

11)	On Smartphone download “Arduino Bluetooth Controller” via Playstore/Appstore. Pair the smartphone with HC-05 module using Bluetooth. After the application has been installed click on   icon to open the application.  On the pop-up window in the application, select the device (HC-05 module). 
 
12)	 The Mode window opens as shown below. Click on the “Controller Mode”
 

13)	 In the Controller Mode click on   symbol.  Select “Set Commands” option.

14)	Change the commands as shown below:
UP ARROW:=6
DOWN ARROW:=4
LEFT ARROW:= 8
RIGHT ARROW:=2
TRIANGLE BUTTON:=Y
CROSS BUTTON:=X
SQUARE BUTTON:=C
CIRCLE BUTTON:=D
START BUTTON:=E
 
15)	On Computer: Click on Tools and select Serial Monitor or press Ctrl+Shift+M. This opens Serial Monitor. We can check the interface between HC-05 and host device.
 
16)	 Press the control buttons on smartphone and check the Command window for output. This verifies the communication between smartphone and HC-05 device.
17)	 
![Screenshot 2 ](https://user-images.githubusercontent.com/115789460/210377827-50da467c-f757-4c12-b2db-c0485ae62c13.png)





![screenshot](https://user-images.githubusercontent.com/115789460/210377864-c2382bbb-6f25-4510-a04e-55b4831f1c70.png)


[miniproject report.docx](https://github.com/srivathsa662001/ROBOTIC-ARM-USING-ARDUINO/files/10337370/miniproject.report.docx)

[final report draft.pdf](https://github.com/srivathsa662001/ROBOTIC-ARM-USING-ARDUINO/files/10337380/final.report.draft.pdf)







