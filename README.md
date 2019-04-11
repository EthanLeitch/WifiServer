# WifiServer
### By Ethan

### What is WifiServer?
The WifiServer program is designed for the WeMos D1 Development Board.
The program connects to WiFi and establishes a web interface.
When a device on the same WiFi goes to a specific page on the web interface, pin D5 is supplied with 3.3V
This could be used to turn a light on and off remotely.

### How do I install WifiServer?

Step 1.
Clone the repository to your computer with the command
> git clone https://github.com/EthanLeitch/WifiServer

Step 2. 
Open the WifiServer.ino file with the Arduino IDE (avalible [here](https://www.arduino.cc/en/Main/Software)

Step 3.
Change the following lines in the program
#define STASSID "YOUR WIFI NAME"
#define STAPSK  "YOUR WIFI PASSWORD"
to your wifi name, and your password.

Step 4. 
Plug in your WeMos D1 to your computer via USB cable.

Step 5.
Select the right port by going into Tools > Ports.
It should be something like /dev/cu.usbserial-4010

Step 6.
Flash the software to the WeMos D1.

Step 7. 
Open the Serial Monitor (Tools > Serial Monitor) and change the baud rate to 115200.

Step 8.
Open your web browser and go to the IP specified in the serial monitor.
