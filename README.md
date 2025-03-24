 Toxic Level Prediction in Lavatory System  

This project is an IoT-based lavatory monitoring system designed to predict toxic gas levels in public restrooms and generate real-time alerts through an Android application. It integrates sensor-based monitoring, machine learning, and Firebase to maintain hygiene and safety.  

Key Features :

- Continuous monitoring using MQ135 gas and PIR occupancy sensors  
- Predictive analytics through Exploratory Data Analysis (EDA) and Linear Regression  
- Automated alert system to notify maintenance teams via the Android application  
- Cloud-based data storage and retrieval using Firebase  
- Intuitive mobile interface for monitoring and alert management  

Technologies Used :

Backend: Python with Pandas, Seaborn, Prophet  
Frontend: Android Studio with Java and XML  
IoT Components: NodeMCU (ESP8266), MQ135 Gas Sensor, PIR Sensor  
Database: Firebase Realtime Database  
Machine Learning: Linear Regression, Exploratory Data Analysis  

Project Modules  :

1. Sensor Module: Detects toxic gas levels and occupancy using sensors, transmitting data to NodeMCU.  
2. Data Analysis Module: Processes sensor data, conducts EDA, and applies linear regression for gas level predictions.  
3. Alert System and Application: Retrieves IoT sensor data from Firebase, compares readings with threshold values, and triggers alerts.  
4. Prediction Module: Utilizes machine learning to estimate future gas levels and enable proactive maintenance.  

Methodology  :

- Real-time data collection from sensors, stored in Firebase  
- Data preprocessing and feature extraction for better analysis  
- Identification of trends and anomalies through EDA  
- Prediction of methane levels using linear regression  
- Alert generation when gas concentration surpasses safe limits  

Future Enhancements  :

- Implementation of deep learning models to enhance prediction accuracy  
- Integration of additional air quality sensors for multi-sensor fusion  
- Application of blockchain technology for decentralized data management  

This project serves as a foundation for exploring IoT-based smart sanitation management, demonstrating the potential of real-time monitoring, predictive analytics, and automated maintenance alerts to ensure hygienic lavatory conditions. Future developments may include enhanced machine learning models, AI-driven ventilation control, and advanced air quality monitoring systems.  

Feel free to explore the code, contribute, or provide feedback.
