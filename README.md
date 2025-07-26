# Smart Arduino Helmet (ResQnet) 🏍️⚡

[![Project Status](https://img.shields.io/badge/status-active-success.svg)]()
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![University](https://img.shields.io/badge/university-Makerere-red.svg)]()

> An intelligent crash detection and emergency response system for motorcycle riders in Uganda, designed to save lives through automated emergency alerts.

![Smart Arduino Helmet](poster/SMART%20ARDUINO%20HELMET.png)

## 🎯 Project Overview

The Smart Arduino Helmet (ResQnet) is an innovative safety solution developed by Computer Science students at Makerere University. This project addresses the critical problem of delayed emergency response for boda boda (motorcycle taxi) riders who are involved in accidents, especially in remote areas or during off-peak hours.

### 🏛️ Academic Information
- **University:** Makerere University
- **College:** Computing & Information Sciences
- **School:** Computing & Informatics Technology  
- **Department:** Computer Science
- **Project Date:** June 2025

## 👥 Development Team

| Name | Student Number | Registration |
|------|---------------|--------------|
| **Tusiime Mark** | 2400711684 | 24/U/11684/PS |
| **Okure Enock** | 2400710690 | 24/U/10690/PS |
| **Namuyimbwa Martha** | 2400709436 | 24/U/09436/PS |
| **Ayebare Atuhaire Eunice** | 2400704071 | 24/U/04071/PS |
| **Weredwong J. Precious** | 2400720747 | 24/U/20747/PS |

## 🚨 Problem Statement

In Uganda, boda boda riders are essential for daily transportation but face significant safety risks:

- **High accident rates** with many resulting in serious injury or death
- **Delayed emergency response** when accidents occur in remote areas
- **Limited affordability** of existing smart safety devices
- **Lack of real-time incident detection** for unconscious or incapacitated riders

## 💡 Solution

Our Arduino-powered smart helmet system provides:

### Automated Crash Detection
- Continuous monitoring using MPU-6050 gyroscope and accelerometer
- Detection of sudden impacts or abnormal head tilts
- Intelligent countdown system to verify rider status

### Emergency Communication
- Automatic SMS alerts via SIM800L GSM module
- Preset emergency contact notifications
- GPS location sharing (future enhancement)

### User-Friendly Interface
- **Single press:** Manual emergency alert
- **Double press:** Cancel false alarms
- Non-invasive design integrated into helmet padding

## ✨ Key Features

| Feature | Description |
|---------|-------------|
| 🚨 **Automatic Crash Detection** | MPU-6050 sensor monitors head movement and detects impacts |
| 📱 **SMS Emergency Alerts** | SIM800L GSM module sends instant alerts to emergency contacts |
| 👆 **Manual Emergency Button** | Single-button interface for manual alerts and false alarm cancellation |
| 🔋 **Rechargeable Battery** | Long-lasting power system for all-day operation |
| 🛡️ **Non-Invasive Design** | Components integrated without compromising helmet safety |
| 💰 **Affordable Solution** | Low-cost Arduino-based design accessible to all riders |

## 🔧 Technology Stack

### Hardware Components
- **Arduino Platform** - Core microcontroller for system control
- **MPU-6050 Sensor** - 6-axis gyroscope and accelerometer for motion detection
- **SIM800L GSM Module** - Cellular communication for emergency alerts
- **GPS Module** - Location tracking for precise emergency response
- **Emergency Button** - Manual control interface
- **Rechargeable Battery** - Sustainable power solution

### Software
- **Arduino IDE** - Development environment
- **C/C++** - Programming language for embedded system
- **GSM AT Commands** - Communication protocols

## 📁 Project Structure

```
Smart-Arduino-Helmet-site/
├── README.md                 # Project documentation
├── LICENSE                   # License file
├── poster/                   # Project poster and images
│   └── SMART ARDUINO HELMET.png
└── website/                  # Project website
    ├── index.html           # Main website file
    ├── css/                 # Stylesheets
    │   ├── controls.css
    │   ├── custom.css
    │   ├── frame.css
    │   └── widgets.css
    ├── js/                  # JavaScript files
    │   ├── custom.js
    │   ├── footer.js
    │   ├── menu.js
    │   ├── util.js
    │   └── widgets.js
    └── videos/              # Demo videos
        ├── meta_mov.mp4
        └── mov_bbb.mp4
```

## 🌐 Website

The project includes a comprehensive website showcasing:
- Problem statement and proposed solution
- Technical specifications and features
- Team information and university details
- Project demonstration videos

To view the website locally:
1. Navigate to the `website/` directory
2. Open `index.html` in a web browser
3. Or serve using a local web server

## 🚀 Getting Started

### Prerequisites
- Arduino IDE
- Basic electronics knowledge
- GSM network access for testing

### Hardware Setup
1. Connect MPU-6050 sensor to Arduino
2. Wire SIM800L GSM module
3. Install emergency button
4. Connect rechargeable battery system
5. Integrate components into helmet padding

### Software Setup
1. Clone this repository
2. Open Arduino IDE
3. Install required libraries:
   - MPU6050 library
   - SIM800L library
   - GPS library (if using)
4. Upload code to Arduino board
5. Configure emergency contact numbers

## 🔮 Future Enhancements

- **GPS Integration** - Exact location coordinates in emergency alerts
- **Mobile App** - Companion app for configuration and monitoring
- **Multiple Contacts** - Support for multiple emergency contacts
- **Health Monitoring** - Integration of heart rate and vital signs sensors
- **Commercial Production** - Partnership with SafeBoda or NGOs for distribution

## 🤝 Contributing

This is an academic project developed by Makerere University students. For questions or collaboration opportunities, please contact the development team.

## 📧 Contact

- **Email:** smartbodahelmet@mak.ac.ug
- **Institution:** Makerere University, Kampala, Uganda
- **Department:** Computer Science

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Makerere University** - College of Computing & Information Sciences
- **Department of Computer Science** - Academic supervision and support
- **Fellow Students and Faculty** - Guidance and feedback throughout development
- **Boda Boda Community** - Inspiration and real-world insights

---

<div align="center">

**Developed with ❤️ by Computer Science Students, Makerere University**

*Revolutionizing motorcycle safety in Uganda through intelligent technology*

</div>