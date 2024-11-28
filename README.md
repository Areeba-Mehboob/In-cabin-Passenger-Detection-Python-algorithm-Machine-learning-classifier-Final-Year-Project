# Child Safety Detection System Using mmWave Radar

## Overview
This project focuses on developing a **Child Safety Detection System** leveraging mmWave radar technology and machine learning. The system is designed to ensure child safety in parked vehicles by monitoring breathing signals and sending notifications to caregivers when necessary.

---

## Problem Statement
Tragic incidents involving children left unattended in vehicles, particularly in extreme weather conditions, emphasize the need for an automated safety solution. This project aims to address this issue by detecting the presence of children based on their breathing patterns and alerting caregivers in real-time. 

---

## Objectives
1. **Signal Acquisition**: Using mmWave radar to capture chest movement data for extracting Breaths Per Minute (BPM).  
2. **Signal Processing**: Filtering raw radar data to isolate breathing signals for accurate analysis.  
3. **Pattern Recognition**: Leveraging machine learning classifiers to identify children based on BPM patterns.  
4. **Alert System**: Integrating a notification mechanism using Twilio to send SMS alerts to caregivers.

---

## Technical Approach
### 1. Hardware Integration
- **mmWave Radar**: Deployed for capturing high-resolution chest movement signals.  
- **Processing Unit**: A Raspberry Pi or equivalent microcontroller processes the radar data.  

### 2. Data Preprocessing
- Noise removal and signal enhancement techniques to ensure the accuracy of the BPM data.  

### 3. Machine Learning
- **Classifiers**: Trained models to detect patterns in BPM data indicative of a child’s presence.
- **Model Validation**: Robust evaluation metrics to ensure reliable performance in diverse conditions.

### 4. Alert Mechanism
- **Twilio API**: Used to send SMS alerts to caregivers with location and situation details.

---

## Project Report
For detailed implementation and access to the code, please refer to the project report available in this repository. The code is included in the appendix section of the report for ease of reference.

---

## Future Improvements
- Integration with additional safety systems such as vehicle alarm triggers.
- Real-time cloud-based monitoring and logging for extended functionality.
- Enhancing the machine learning model for broader age group detection.

---

## Acknowledgments
Special thanks to all contributors and mentors who supported the successful completion of this project.

---

## Contact
For any queries or contributions, feel free to reach out at:  
**Email**: [Your Email Address]  
**LinkedIn**: [Your LinkedIn Profile]
