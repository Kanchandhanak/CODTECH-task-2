Name : KANCHAN DHANAK 

Company : CODTECH IT SOLUTIONS 

ID : CT08DS4895

Domain : INTERNET OF THINGS

Duration : 15 JULY TO AUGUST 2024

Mentor : NEELA SANTHOSH KUMAR 

Overview of the project 

Project : Develop to use IOT-basis weather monitoring station.

Objective 

The objective of this  project is to perform this code to create an IoT monitoring station using an ESP32 microcontroller and a BME280 sensor to collect data on temperature, humidity, and atmospheric pressure. The collected data is then sent to a backend server over Wi-Fi at regular intervals (every minute) for storage and further analysis. Here’s a detailed breakdown of the objectives:


Key activities 

Here's an overview of the key activities involved in building the IoT monitoring station:

1. Hardware Setup
1.1. Gather Components:
   
 Microcontroller: ESP32
 Sensor: BME280
Power Supply: USB power adapter or battery pack
Breadboard and Jumper Wires

1.2. Connect Components:

Connect the BME280 sensor to the ESP32 using jumper wires:
  VCC to 3.3V
  GND to GND
  SCL to GPIO 22
  SDA to GPIO 21

1.3. Ensure Power Supply:

 Connect the ESP32 to a USB power adapter or battery pack.

2. Microcontroller Programming

2.1. Install Arduino IDE:

 Download and install the Arduino IDE.

2.2. Install Necessary Libraries:

Open Arduino IDE, go to `Sketch` -> `Include Library` -> `Manage Libraries`, and install:
  `Adafruit BME280`
  `Adafruit Unified Sensor`
  `WiFi`

2.3. Write and Upload Code:

Write a program in the Arduino IDE to read data from the BME280 sensor and send it to the backend server over Wi-Fi.
Upload the code to the ESP32.

3. Backend Server Setup

3.1. Install Python and Flask:

Install Python from the official website.
 Install Flask and SQLAlchemy using pip:
  ```sh
  pip install Flask SQLAlchemy
  ```

3.2. Write Backend Code:

 Create a Flask application to handle data received from the ESP32 and store it in a SQLite database.

3.3. Run the Backend Server:

Run the Flask application locally or deploy it on a cloud platform like Heroku or AWS.

4. Database Setup

4.1. Define Database Model:

 Define a model for storing sensor data in the SQLite database.

4.2. Create Database:

 Initialize and create the database using Flask and SQLAlchemy.

5. Front-End Application

5.1. Create a Web Page:

Develop a simple HTML page to display real-time sensor data

6. Deployment and Testing

6.1. Deploy Backend Server:

 Deploy the Flask server on a platform like Heroku, AWS, or a local server.

6.2. Test Microcontroller:

 Ensure the ESP32 is sending data correctly to the backend server.

6.3. Test Front-End Application:

 Verify the front-end application displays the data in real-time.

6.4. Debug and Iterate:

Debug any issues and iterate on the design and implementation as needed.

Technologies use

Microcontroller Programming: Using ESP32 for IoT applications.
 
Sensor Integration: Using the BME280 sensor to gather environmental data.
  
Wi-Fi Networking: Connecting to Wi-Fi and sending data to a remote server.

HTTP Communication: Using HTTP POST requests to transmit data.

Embedded C++: Writing and running code on a microcontroller.

Error Handling and Data Validation:** Ensuring reliable and accurate data transmission.
