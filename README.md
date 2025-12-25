## SAFEJOURNEY: Smart IoT Safety Device for Women Scooter Riders
SAFEJOURNEY is an IoT-based safety system designed to enhance the safety of women scooter riders by detecting emergency situations and automatically sending alert messages with location details to predefined contacts.

## About
SAFEJOURNEY is a research-based mini project that focuses on women’s safety during two-wheeler travel. Women scooter riders often face emergencies such as accidents or unsafe situations where immediate assistance is required. Traditional safety solutions rely heavily on manual intervention, which may not always be possible.
This project proposes an IoT-enabled safety mechanism that continuously monitors rider conditions and automatically triggers emergency alerts during abnormal situations. The system supports both automatic emergency detection and panic alert generation, ensuring timely communication of the rider’s location to emergency contacts. The project functionality is demonstrated using simulation, making it suitable for academic and research purposes.

## Features

Automatic detection of abnormal motion indicating emergency situations

Panic alert mechanism for emergency triggering

Emergency alert message with location details

Simulation-based implementation for easy testing

Low-cost and scalable design

Suitable for two-wheeler safety applications

Fast response and minimal processing delay

## Requirements
# Hardware Requirements (Optional – for real implementation)

Arduino Uno / ESP32 (optional)

Accelerometer sensor (e.g., MPU6050)

GPS module (optional)

GSM / IoT communication module (optional)

# Software Requirements
Operating System: Windows 10 / Ubuntu (64-bit)

Development Environment: Arduino IDE

Simulation Tool: Wokwi (Online Arduino Simulator)

Programming Language: Embedded C / Arduino C

Version Control: Git and GitHub

## System Architecture

<img width="282" height="450" alt="image" src="https://github.com/user-attachments/assets/daf00787-e73c-466c-9141-5e53e7849c98" />

The proposed Safe Journey system is built on an ESP32 microcontroller integrated with GPS, accelerometer, gyroscope, GSM module, Bluetooth module, and a panic switch. The ESP32 continuously monitors real-time data from motion sensors to detect abnormal patterns such as fall, skid, theft, or collision. The GPS module provides live coordinates, while the GSM module handles SMS alerts. Bluetooth acts as a fallback channel when GSM connectivity is poor. All components operate on a rechargeable battery, ensuring uninterrupted functionality. The system architecture is designed to provide redundancy, quick detection, and multi-channel communication for enhanced safety.

## Output

#### Output1 - System Initialization

<img width="827" height="528" alt="image" src="https://github.com/user-attachments/assets/2bbecda6-25a0-4220-bb61-fcc0c33b421f" />


#### Output2 - Panic Alert with Location

<img width="528" height="445" alt="image" src="https://github.com/user-attachments/assets/d28897d1-8f31-4f37-a9cb-725c9d467d70" />

## Results and Impact

The SAFEJOURNEY system demonstrates how IoT technology can be effectively used to enhance women’s safety during scooter travel. By enabling real-time emergency detection and alert generation, the system reduces response time and improves personal safety. This project highlights the potential of IoT-based safety solutions in smart transportation systems and serves as a foundation for future real-time implementations.

## Articles published / References

·  Chen, L., et al. (2017). Continuous Vehicle Tracking Using GPS and GSM Technologies. IEEE Transactions on Intelligent Transportation Systems.

·  Vijayalakshmi, S., & Elango, R. (2017). IoT-Based Smart Vehicle Tracking and Theft Prevention System. International Journal of Advanced Research in Computer Science.

·  Arvind, K., & Senthil, M. (2018). Real-Time Vehicle Tracking Using IoT. Springer Proceedings of Smart Computing.

·  Dong, Y., et al. (2020). WatchDog: Edge-Based Real-Time Vehicle Tracking with IoT. arXiv preprint.

·  Li, H., et al. (2020). Vehicle Tracking Using Deep Reinforcement Learning with IoT Sensors. arXiv preprint.

·  Balani, S., & Mustafa, K. (2024). Developing Vehicle Monitoring Systems via IoT and GSM. International Journal of Intelligent Systems and Applications Engineering.

·  Silva, P., et al. (2025). Real-Time Vehicle Tracking Using IoT, Geolocation, and Cloud Infrastructure. International Journal of Computer Science.

·  Sahu, P., & Behera, R. (2019). Personal Safety Alert System Using Bluetooth Low Energy. IEEE Conference on Communication and IoT.

·  Dixit, S., & Kapoor, V. (2020). IoT-Enabled Panic Alert System for Women Safety. International Journal of Engineering Research & Technology.

·  Rawat, R., & Garg, A. (2019). Women Safety System Using IoT with GSM Module. IEEE International Conference on Electronics and Communication Systems.

·  Aditya, P., & Sharma, R. (2021). GPS and GSM-Based Women Safety Alert Device. International Journal of Innovative Research in Computer Science.

·  Rathod, V., & Chauhan, A. (2019). Women Safety Using Wireless Sensor Networks and IoT. Springer Advances in Intelligent Systems.

·  Harikiran, J., et al. (2016). Smart Security Solution for Women Using IoT. Springer Smart Innovation, Systems and Technologies.

·  Ahir, S., et al. (2018). The Personal Stun – Women Safety Device. Springer Lecture Notes in Electrical Engineering.
