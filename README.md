# Fish Farm Monitoring System 🐟🌊  

An open-source, IoT-powered fish farm monitoring system with real-time data visualization, AI consultation, AI insights, and automated reporting.

---

## Features ✨  
1. **Real-Time Data Monitoring**: View live data for pH, TDS, turbidity, temperature, and more.  
2. **AI-Powered Insights**: Get Bangla suggestions based on sensor data through the App and Website.  
3. **Data Visualization**: Graphs for historical trends and analysis, available in both App and website.  
4. **AI Consultation (Chatbot)**: Ask fish farming-related questions in Bangla.  
5. **Manual Testing**: Trigger tests via the mobile app or Website.  
6. **Daily Reports**: Automatically generated summaries and insights.  
7. **Predicted Metrics**: Includes AI-predicted **dissolved oxygen** and **ammonia levels** to ensure water quality.  
8. **Auto Calibration**: Sensors automatically calibrate to maintain accuracy.
9. **Mobile App Dashboard**: Monitor data and access reports via a user-friendly Mobile App interface.
10. **Website Dashboard**: Monitor data and access reports via a user-friendly web interface.

---

## System Overview  
### **Hardware**
- **Microcontrollers**:  
  - Arduino Uno R3  
  - NodeMCU (ESP32)  

- **Sensors**:  
  - pH, TDS, Turbidity, Temperature, etc.  

- **Power Supply**:  
  - Solar panel (5W) and 18650 batteries  

- **Additional Components**:  
  - Relays for power control
  - GSM Module
  - Blynk for initial connectivity testing  

- Circuit diagram and setup instructions: [Hardware Setup](hardware/README.md)  

### **Software**  
- **Mobile App**:  
  - Built with **Flutter**, powered by **Firebase** for real-time data synchronization.  
  - Features include real-time data display, manual test initiation, AI chatbot, and daily insights.  
  - Detailed guide: [Will be updated Soon!]

- **Backend**:
  - **Python**: Used for backend logic, sensor data processing, and AI model integration. 
  - **Firebase**: Handles data storage, authentication, and real-time updates.  
  - **AI Integration**: Powered by OpenAI API for generating insights and predictions.  

- **Web Dashboard**:  
  - Built for desktop and mobile browsers.  
  - Displays live sensor data, historical graphs, and daily reports.
  - AI-generated insights, including recommendations in Bangla based on real-time data and sensor predictions.
 

---

## Contributing 🌟  
Contributions are welcome!  

---

## Links 🌐  
- **Live App Demo**: [Will be updated Soon!]
- **Website Dashboard**: [Will be updated Soon!]

---
