🌬️ Real-Time Data-Driven Intelligent IoT-Based Wind Energy Management System
🧑‍💻 Developed by:
Janarthanan. S, Jayaraj. V, Pranav. G
Guided by: Ms. G. Yasika, Assistant Professor
VSB Engineering College (Autonomous)

📌 Project Overview
This project implements an intelligent renewable energy system leveraging wind power combined with IoT-enabled monitoring and smart energy distribution. By integrating sensors, Arduino, and IoT platforms, it ensures optimal power generation, real-time control, and remote access — making it highly suitable for off-grid or smart grid applications.

⚡ Abstract
The system:

Captures wind energy through a turbine.

Stores surplus power in a rechargeable battery.

Monitors wind speed, battery voltage, and temperature using sensors.

Displays real-time system data on an LCD screen.

Uses an Arduino Uno for control logic.

Enables remote monitoring and control using ESP8266 (NodeMCU) via platforms like Blynk and ThingSpeak.

Integrates a DC-DC converter, relay, and inverter to ensure stable power flow and distribution.

🎯 Objectives
✅ Harness wind energy efficiently.

✅ Optimize energy storage using battery.

✅ Monitor system parameters like voltage and temperature in real-time.

✅ Enable smart energy distribution with both automatic and manual control.

✅ Provide IoT-based remote control and data visualization.

🔍 Literature Survey
The project draws upon research in:

Cost reduction in wind turbines.

Techno-economic modeling of small-scale wind systems.

MPPT algorithms for wind energy harvesting.

Hardware simulations for wind turbine performance testing.

Wind turbine drivetrain noise and vibration analysis.

(See References section below for complete sources.)

🔧 System Design
🔸 Hardware Components
Arduino Uno

Voltage Sensors

Temperature Sensor (e.g., DHT11)

DC-DC Converter

Relay Module

Inverter

LCD Display

ESP8266 WiFi Module

🔸 Software Tools
Arduino IDE (programming & uploading sketches)

Proteus (circuit simulation)

Blynk / ThingSpeak (IoT platforms)

🔸 Key Features
Real-time data acquisition & display

Remote turbine/load control via IoT

Power regulation & conversion

Modular and scalable system architecture

🔄 Existing vs Proposed System
-----------------------------------------------------------------------------------------------------------------
Feature	                                 Existing Systems	                          Proposed System
------------------------------------------------------------------------------------------------------------------
Monitoring	                             Manual / Limited	                    Real-time via sensors + IoT
Control Mechanism	                            Manual	                    Automated + Remote (via relay & IoT)
Energy Efficiency	                           Moderate	                   Optimized using real-time adjustments
Remote Accessibility	                   Rarely available	                     Fully integrated with IoT

🖼️ Block Diagram
(Add a block diagram image here if you have one — system architecture showing sensor → Arduino → IoT module → load etc.)

✅ Advantages
📡 IoT-Enabled Monitoring – Control & monitor the system from anywhere.

⚙️ Efficient Energy Flow – Reduces wastage and improves system lifespan.

📈 Real-Time Data – Fast response to changing wind conditions.

🌱 Eco-Friendly – Supports clean, green, and sustainable energy initiatives.

🧪 Results & Discussion
✔️ Simulation validated using Proteus before real-world implementation.

✔️ Real-time sensor data transmitted via ESP8266 to ThingSpeak/Blynk.

✔️ Reliable switching and monitoring achieved through Arduino and relays.

✔️ Highly scalable design for rural and remote deployments.

📸 Project Output
✅ IoT Dashboard screenshots (On/Off states)

✅ Hardware Prototype Images

✅ Sensor Value Visualizations

(Include project screenshots here if available.)

🧾 Conclusion
This intelligent wind energy system showcases how renewable power can be harnessed smartly, stored effectively, and controlled remotely. It merges embedded systems, IoT, and power electronics to deliver a low-cost, high-impact solution suitable for smart villages, disaster zones, and green tech environments.

📚 References
Elia et al., Wind turbine cost reduction, Energy Policy, 2020.

De Kooning et al., Optimisation of small wind turbines, SETA, 2021.

Zouheyr et al., MPPT hardware implementation, Energy, 2021.

Ajirlo et al., Designing HAWT simulators, SETA, 2021.

Xu et al., Wind turbine drivetrain vibration review, SETA, 2021.

