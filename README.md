# Real-Time Sensor Data Monitoring with Arduino and Flask

This project demonstrates a real-time monitoring system that reads data from an MQ-135 gas sensor connected to an Arduino and displays it on a web interface. The application leverages Flask for the backend, Socket.IO for real-time communication, and a simple frontend interface for data visualization. The system also includes hardware components such as LEDs and a buzzer for local alerts based on sensor readings.

## Hardware Components
- **Arduino Uno**: The microcontroller board used to interface with the sensor and other hardware components.
- **MQ-135 Gas Sensor**: Used for detecting gas concentrations in the environment.
- **LCD Display**: Displays sensor readings and alerts locally.
- **LEDs (Red and Green)**: Indicate the status of the environment (normal or alert).
- **Buzzer**: Provides audible alerts when gas concentrations exceed a certain threshold.

## Features
- **Real-Time Data Display**: Continuously reads data from the connected MQ-135 sensor and updates the web interface every second.
- **Socket.IO Integration**: Utilizes Socket.IO to emit real-time sensor data from the server to the client.
- **Efficient Data Logging**: Logs sensor data to a text file, ensuring only the latest readings are kept.
- **Local Alerts**: The Arduino controls LEDs and a buzzer to provide immediate local alerts when dangerous gas levels are detected.
- **Research Publication**: This project is backed by a research paper published on the same topic, demonstrating its scientific and practical relevance.

## Software Components
- **Flask**: A lightweight WSGI web application framework in Python.
- **Socket.IO**: Enables real-time, bidirectional communication between web clients and servers.
- **HTML/CSS**: Frontend technologies used to create the web interface.

## Setup Instructions
1. **Setup Arduino**: Upload the provided Arduino code to your Arduino Uno.
2. **Install Python Dependencies**: Install Flask and Socket.IO using `pip`.
   ```bash
   pip install flask flask_socketio
   python app.py
3. Run Flask Server: Start the Flask server to serve the web application.
   python app.py
5. Open Web Interface: Navigate to http://localhost:5000 to view real-time sensor data.
##Research Publication
This project is backed by a research paper titled "[A Case Study on the Marketing Implications of using Smart Gas Leakage Detectors in Industrial Facilities](https://www.scopus.com/record/display.uri?eid=2-s2.0-85191876480&origin=resultslist&sort=plf-f&src=s&sid=dcc807bcdd774c8a0bf5f3a807c021ce&sot=b&sdt=b&s=AUTH%28Annjan%29&sl=12&sessionSearchId=dcc807bcdd774c8a0bf5f3a807c021ce&relpos=0)," presented at the 3rd International Conference on Innovative Mechanisms for Industry Applications (ICIMIA 2023).

##Lisence
[MIT LISENCE](MIT LISENCE)

