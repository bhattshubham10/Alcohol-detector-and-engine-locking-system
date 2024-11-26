# Alcohol-detector-and-engine-locking-system
The Alcohol Detection and Engine Locking System is designed to prevent drunk driving by 
automatically detecting the driver's alcohol consumption and disabling the vehicle’s ignition if 
the alcohol level exceeds the legal limit. The system uses an MQ-3 alcohol sensor to measure 
the blood alcohol concentration (BAC) from the driver's breath. The Arduino Uno 
microcontroller processes the sensor data and compares it with a predefined BAC threshold. If 
the threshold is exceeded, the system activates an engine lock by controlling a relay, preventing 
the vehicle from starting or continuing to operate. The system also provides real-time feedback 
to the driver through an LCD display, LED indicators, and a buzzer, which alerts the driver 
about the detected alcohol concentration. 
This intelligent and compact system is suitable for integration into various types of vehicles and 
can be discreetly installed. The proposed system offers enhanced safety by reducing alcohol
related road accidents, making it an essential tool for public safety. The system is also designed 
to be cost-effective, reliable, and efficient, ensuring practical use in real-world applications. 
Future enhancements could include integration into vehicle manufacturing, bringing a new level 
of innovation to automobile safety technology and contributing to the reduction of drunk driving 
incidents.

Alcohol Detection Techniques: 
Various studies focus on developing efficient methods for alcohol detection in drivers, with 
breath alcohol sensors (like MQ-3 and MQ-2) widely used for their sensitivity to alcohol 
content in the air. In Yadav and Singh’s work (2018), the MQ-3 sensor was implemented to 
identify breath alcohol levels with an Arduino, emphasizing its affordability and ease of 
integration in safety applications other approach by Zahran et al. (2019) highlights the 
integration of alcohol detection systems into vehicles to assess blood alcohol concentration 
(BAC) accurately. This research demonstrated that breath-based sensors, despite their cost
effectiveness, could be improved in accuracy by addressing issues like temperature sensitivity 
and calibration requirements. 
king Mechanisms: 
Studies often pair alcohol detection with automatic engine control, aiming to prevent drunk 
driving incidents. Kumar et al. (2020) explored a system where, upon detecting a BAC above 
the legal limit, the microcontroller locks the vehicle’s ignition. This study emphasized the 
importance of timely response and accurate detection to prevent unauthorized vehicle 
operation, although it highlighted the need for reliable sensor calibration in real-world settings. 
Similarly, and Chauhan* (2021) designed a prototype system that used a relay connected to 
the Arduino to control the ignition circuit. Their findings showed that this simple design could 
be effective but was prone to false positives in environments with strong odors or other 
contaminants that might trigger the sensor inadvertently. 
Microcontroller Embedded Systems: 
Arduino Uno, equipped with the ATmega328 microcontroller, is frequently selected for these 
types of safety systems due to its flexibility and user-friendly programming environment. Patil 
and Nalawade (2019) described a system using Arduino Uno as a core component, noting its 
ease of integration with sensors and relays for vehicle safety applications. They further 
demonstrated that Arduino-based systems are feasible for small, standalone applications but 
may require additional modules for large-scale, commercial use. 
Challenge Alcohol Detection Accuracy: 
Research by Vidhya and Raghavendra (2022) indicates that environmental factors like 
temperature and humidity can affect the accuracy of MQ-series sensors, making recalibration 
necessary for consistent results. Their study suggests that integrating multiple sensors or using 
supplementary environmental sensors could improve overall reliability, especially when 
deployed in different vehicle types or geographical locations. 
Safety Public Acceptance: 
A study by Agrawal and Srivastava (2020) highlighted the broader safety implications of 
implementing alcohol detection systems in vehicles, showing that public acceptance and 
awareness play a critical role in adoption. They found that while such systems have proven 
effective in prototypes, widespread implementation requires addressing user concerns about 
privacy, cost, and reliability.

OBJECTIVE 
The primary objective of the alcohol detector and engine locking system using Arduino Uno 
and MQ-3 sensor is to prevent drunk driving by disabling a vehicle’s ignition if the driver’s 
blood alcohol concentration (BAC) exceeds a specified threshold. Here’s a breakdown of the 
main goals of the system: 
Enhance Road Safety: The system aims to reduce alcohol-related road accidents by detecting 
when a driver is intoxicated and preventing vehicle operation, thus minimizing the risk of 
impaired driving incidents. 
Real-Time Alcohol Detection: By using the MQ-3 sensor, the system continuously monitors 
alcohol levels in the driver’s breath and provides immediate feedback, allowing for quick 
intervention if the BAC is above the legal limit. 
Automated Engine Control: The system’s integration with the vehicle’s ignition system 
enables it to automatically lock the engine if alcohol is detected, thereby removing the manual 
decision-making process and ensuring consistent safety enforcement. 
Cost-Effective and Compact Solution: Designed with low-cost and readily available 
components like the Arduino Uno, this system is intended to be affordable and compact, making 
it suitable for integration into a wide range of vehicle models. 
Promote Responsible Driving Behaviour: By incorporating a technological deterrent against 
drunk driving, this system serves as a preventive measure that encourages drivers to avoid 
alcohol consumption before operating a vehicle. 
Overall, the system’s objective is to offer an effective, automated solution to curb drunk driving, 
contributing to safer road environments and aligning with broader public safety and sustainable 
development goals.
