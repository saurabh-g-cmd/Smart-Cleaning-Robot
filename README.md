# Smart-Cleaning-Robot
🤖 Smart Mopping Robot using ESP32

A fully autonomous and web-controlled smart cleaning robot developed using the ESP32 microcontroller. This robot is designed to perform intelligent floor cleaning by combining vacuum cleaning, hydraulic mopping, water spraying, and obstacle avoidance into one compact robotic system. The robot creates its own WiFi hotspot, allowing users to control it directly from any smartphone, tablet, or laptop browser without installing any external application.

The system supports both manual and autonomous cleaning modes. In manual mode, the robot can move in all directions using responsive web-based controls. In automatic mode, the robot uses multiple ultrasonic sensors to detect obstacles from the front, left, and right sides, enabling safe navigation and automatic path correction. An IR cliff sensor is also integrated to prevent the robot from falling from edges such as stairs or tables.

The cleaning mechanism consists of three independent systems: a hydraulic water spraying system, a mopping mechanism, and a vacuum suction system powered by a BLDC motor. These components work together to provide efficient wet and dry cleaning. The water pump sprays controlled amounts of water onto the floor while the microfiber mop cleans the surface, and the vacuum motor removes dust and debris simultaneously.

A modern responsive web dashboard is developed for real-time robot interaction. The interface displays live sensor values, movement controls, cleaning controls, mode status, and safety alerts. The UI automatically adapts to both mobile and desktop screen sizes, providing a smooth user experience across all devices.

The project demonstrates the practical implementation of IoT, embedded systems, robotics, sensor integration, automation, and wireless communication in a real-world smart cleaning application. It can further be upgraded with AI-based navigation, voice control, live camera streaming, room mapping, and mobile application integration.

✨ Features

📱 Responsive Web Control UI
🤖 Auto + Manual Navigation
🚧 Front, Left & Right Obstacle Detection
⚠️ IR Cliff/Fall Protection
💧 Hydraulic Water Spraying System
🧹 Mopping Mechanism
🌪️ Vacuum Cleaning using BLDC Motor
📡 ESP32 WiFi Access Point Control
📊 Live Sensor Status Monitoring
🔄 Real-Time Browser Updates
⚡ Smooth Multi-Directional Movement

🛠️ Technologies Used
ESP32 Microcontroller
Embedded C++ Programming
HTML/CSS/JavaScript Web Interface
IoT and Wireless Communication
Ultrasonic Sensor Integration
Relay Control System
Robotic Motion Control
Autonomous Navigation Logic

🌐 WiFi Access
SSID: SMART_ROBOT
Password: 12345678

Open in browser: 192.168.4.1
