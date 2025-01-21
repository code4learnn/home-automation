# home automation system using the Nodemcu ESP8266 board and the new Blynk app

## Project Overview
This project demonstrates the development of a Home Automation System using the NodeMCU ESP8266 board and the new Blynk application. The system allows users to control home appliances such as lamps, fans, or televisions through a smartphone app or a web dashboard. This project serves as a practical implementation of Internet of Things (IoT) principles, showcasing real-time interaction between hardware and software.

## Approach and Implementation

1. Component Identification and Setup:
The following components were used to create the system:

* NodeMCU ESP8266 Board
* Two-Channel Relay Module
* Two Bulbs with Holders
* Plug Top
* Jumper Wires
* Breadboard

Each component was carefully identified and prepared for integration into the circuit.

2. Circuit Assembly:

* The NodeMCU board was connected to the breadboard.
* Bulb holders were wired to the relay module according to the provided circuit diagram.
* The plug top was connected to the 230VAC input to power the appliances.
* The relay module was connected to the NodeMCU using jumper wires.

3. Blynk Web Application Configuration:

* A Blynk account was created, and a new template was set up with hardware set to ESP8266 and Wi-Fi connection type.
* Two virtual pins (V0 and V1) were configured as data streams for controlling two appliances.
* Buttons were added to the web dashboard, mapped to the virtual pins, and configured to act as switches.

4. Programming the NodeMCU:

* The project’s firmware was written in C++ using the Arduino IDE.
* Libraries for ESP8266 and Blynk were included.
* Relay pins (D0 and D1) were defined and configured as output pins.
* The program read button inputs from the Blynk app and controlled the relays accordingly.

5. Mobile App Configuration:
* The Blynk app was installed and set up on a smartphone.
* Buttons corresponding to the virtual pins were added to the app dashboard and configured to toggle the relays.

6. System Testing:
* The NodeMCU board was powered using a 5V DC supply.
* Bulbs were installed in their holders, and the system was connected to AC power.
* The appliances were successfully controlled via the Blynk app and web dashboard.

## Tools and Technologies Used

* Hardware:
  * NodeMCU ESP8266 board
  * Relay module
  * Breadboard and jumper wires

* Software:
  * Arduino IDE for programming
  * Blynk app for mobile and web interfaces
  * Libraries: ESP8266WiFi, BlynkSimpleEsp8266

* Others:
  * Circuit diagrams and prototyping equipment

##  let’s do this project step by step

# Step 1
Firstly, identify these components.

![image](https://github.com/user-attachments/assets/c685248d-1980-455e-862c-d208ac682e80)


![image](https://github.com/user-attachments/assets/3792e4ef-94b2-45a3-807a-dae3453bfc98)

![image](https://github.com/user-attachments/assets/913c3cf2-2381-4a87-967d-701d667fc1b5)

![image](https://github.com/user-attachments/assets/607ab715-5703-45cd-9684-be0dea5f78e9)

![image](https://github.com/user-attachments/assets/23790c38-b168-4a84-b290-0ece20ce1e48)

![image](https://github.com/user-attachments/assets/7d730a63-ecb8-4321-b060-fa44e1aeea4f)

![image](https://github.com/user-attachments/assets/e55e8ad8-9398-4d36-85df-df30f7c14487)

![image](https://github.com/user-attachments/assets/19b0b96a-5b8a-467a-b38c-05aca64face9)

# Step 2

Secondly, connect the Nodemcu board to the breadboard.

![image](https://github.com/user-attachments/assets/92b5aa4b-c19b-4bee-bd66-554e72656b1b)

# Step 3
Thirdly, connect the bulb holders to the relay module. For that, use the circuit diagram below.

![Screenshot 2025-01-21 131112_processed](https://github.com/user-attachments/assets/a26c4e18-ec10-427d-8ab2-7db9ba812b33)

![image](https://github.com/user-attachments/assets/0057f05b-3a4a-4760-a74c-1442875d8e17)


# Step 4
Next, connect the plug top to the 230VAC input point.

![image](https://github.com/user-attachments/assets/7023e85b-192c-41b8-815e-67745cffc184)

![image](https://github.com/user-attachments/assets/837baf20-a89c-47c3-aad0-d3c724aad415)

# Step 5
OK, now connect the relay module to the Nodemcu board using the jumper wires. For that, use the circuit diagram above. Next, connect it to the computer.

![image](https://github.com/user-attachments/assets/d9f9bf38-c32a-44ce-819f-a707ff00efa5)

![image](https://github.com/user-attachments/assets/8dd16b9c-8493-4ee4-b931-7dd3288dde39)

# Step 6
Now, let’s set up the Blynk web application step by step. For that, follow the instructions below.

First, go to the Blynk official website using your browser. Then login to this site using your email and password. (If you don’t have a Blynk account, you must make a new account. For that, use this link. It will guide you)

![image](https://github.com/user-attachments/assets/f4a5d2a5-b6aa-4095-9dc1-5abb39b0c805)

![image](https://github.com/user-attachments/assets/8388625b-ab48-4f42-9523-737324d2742e)

![image](https://github.com/user-attachments/assets/969ecb2d-0a53-4979-b3d4-a719066b8f54)

* Next, click the template button and create a new template . For that, name it as you like. Also, select the hardware as ESP8266 and the connection as WIFI.
![image](https://github.com/user-attachments/assets/282b45f6-2f41-444b-a677-c8e1a88ecb6a)

![image](https://github.com/user-attachments/assets/cecfb688-36cf-40ab-9979-2a24c47e902f)

* Then, click the “Datastreams” tab and create two Datastreams as VitualPin. Also, set the first pin and the second pin to V0 and V1. Then, select the data type as an integer.
![image](https://github.com/user-attachments/assets/406bea55-2b92-4d27-a4a3-3807dbf195e2)

![image](https://github.com/user-attachments/assets/f8aa7616-e310-4102-9aed-a7f5a141c953)

![image](https://github.com/user-attachments/assets/4e00e3d7-021f-4abd-8c99-d7c8f962b1d4)

![image](https://github.com/user-attachments/assets/50b9ef8b-45a4-49d0-819c-a5e5da1244eb)

* Now, click on the Web Dashboard tab. Then, drag and drop two buttons to the dashboard. Next, click the setting icon in the button and select the datastream we created earlier. That is, V0 for button one and V1 for button two. Finally click the save button.

![image](https://github.com/user-attachments/assets/61955b81-5edf-4d68-a2e2-412f991bdcd6)

![image](https://github.com/user-attachments/assets/42eac902-0567-48d6-8d8d-52d96f6aba50)

![image](https://github.com/user-attachments/assets/5f081d64-1125-48f9-9f86-671050d70b7f)

![image](https://github.com/user-attachments/assets/e2a71e01-900d-440b-b886-da17ef9062cc)

![image](https://github.com/user-attachments/assets/9297956c-9cf0-4785-87d8-5d260fd7aece)

![image](https://github.com/user-attachments/assets/24ec9fb0-9fc6-4b66-9ca2-e9a4251ae167)


* Step 7
now let’s create the program for this project. It’s as follows.

![image-1](https://github.com/user-attachments/assets/6505330e-90ad-46ef-8202-b3efebc3f599)

* copy and paste the Blynk auth token. To do this, check the “Device Info” tab of your Blynk web application.

* Next, enter your correct WIFI name and password.

# Step 9
Now, connect the 5 VDC external power supply to the Nodemcu board. For that, use the circuit diagram above.

![image](https://github.com/user-attachments/assets/3c712b53-948b-4bea-923e-6ad1af94df35)

# Step 10

Finally, put the bulbs to the holders and connect the plug top to the AC voltage. 

## Learnings

* IoT Concepts
* Hardware-Software Integration
* Circuit Design
* Blynk Platform
* Programming

##  Output and Results

The project resulted in a fully functional home automation system capable of controlling two appliances through a smartphone app or web dashboard. Key outcomes include:

* Reliable Performance: The system allowed seamless and responsive control of appliances with minimal delay.
* Scalability: The system design makes it easy to expand by adding more relays to control additional devices.
* User-Friendly Experience: Both the web and mobile dashboards provided an intuitive and straightforward interface for users.


## contact profile: 

* linkedin Profile : https://linkedin.com/in/suryansh-pratap-singh-55b9b4226
* leetcode Profile : https://leetcode.com/u/code4learnn/
* github link : https://github.com/code4learnn/home-automation
