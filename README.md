 Software Installation for NodeMCu..
 
 1. Arduino IDE and Drivers for NodeMCU
 Step by Step Procedure :

1. First of all go the Arduino Website (www.arduino.cc) and click on the
software and as per our operating system download the Arduino IDE on your
computer system.
2. After downloading of the IDE on your system Run the Arduino.exe (For
windows) and once the IDE launched close the application.
3. Now We need to install the drivers for our NodeMCU Board so click
on the link below to download the driver for the windows. 
FOR NODEMCU :
https://www.silabs.com/documents/public/software/CP210x_Windows_Drivers.zip

And for NODEMCU CH341SER
https://github.com/nodemcu/nodemcu-devkit/blob/master/Drivers/CH341SER_WINDOWS.zip

Click on windows to download the drivers
4. After downloading done, install the driver on your system and restart the
computer.
5. Now after restarting your computer, we need to install the board libraries for
NodeMCU. So launch the Arduino IDE/application and click on files
tab and then go to preferences
6. Once Preferences window opens, you can see additional Boards manager at
the bottom. So in that column paste the below mentioned URL and click on
OK
http://arduino.esp8266.com/stable/package_esp8266com_index.json


7.Once the board manager opens, in search bar type “nocemcu/Wemos D1” ,
immediately you will get the nodemcu/Wemos Library

8. Click on the install and wait for some time, as it will get few
minutes(depending upon your internet speed) to download and install on
your system
9. Once the library installed close the window and click on the Tools&gt;Boards and
you will get the list of Arduino and other boards then choose the
NodeMCU1.0/Wemos board from board list.

10. Now again click on tools and set the below mentioned parameters one by
one
a. CPU Frequency : 80 MHz
b. Flash size : 4M
c. Upload Speed :115200
d. Port : COMport XX Will see during Works

Now Connect nodemcu  with laptop and go to  tools and then port Selecet COM3/COM4/....COM9
NOW ALL SET LETS BLINK LED :)
