# 🌈 Stress Monitoring and Therapy Recommendation System

This project integrates both **hardware and software** components to detect the stress levels of mentally ill children using physiological data and provide suitable therapeutic activities via a mobile app. 
Based on real-time stress analysis, the system dynamically recommends interactive activities like puzzles, music therapy, or yoga, fostering mental stability and emotional wellness.

## 🎯 Problem Statement

Mentally ill children often struggle to express their emotions clearly, making it difficult for caregivers to identify stress levels in real-time. 
Traditional therapy methods lack personalization and fail to address rapid emotional shifts. This system aims to bridge that gap through a wearable-driven approach that automatically identifies stress and 
provides timely activity-based therapy.

## 💡 Features

- Real-time stress detection using heart rate monitoring
- Activity recommendations based on stress thresholds (High, Moderate, Peaceful)
- Mobile app with engaging UI for kids
- Automated transitions between therapy levels
- Secure data handling via Azure and Render

## 📱 Mobile App Interface

The mobile app is developed in Flutter and provides:
- Welcome screen with an engaging design
- Activity levels: High Stress, Moderate, Peaceful
- Game-like activities (e.g., Spot the Difference, Puzzle Solving)
- Real-time synchronization with hardware data via Bluetooth

## 🧠 System Architecture

### Hardware
- **ESP32 Microcontroller** – Heart of the system
- **Pulse Sensor** – Captures heart rate data
- **Bluetooth Module** – Wireless communication with mobile app

### Software
- **Flutter** – Mobile app development
- **Arduino IDE** – Programming the microcontroller
- **Render** – Keeps the server alive for backend processing
- **Microsoft Azure** – Handles secure authentication and cloud data storage

## 🔄 Methodology

1. The ESP32 reads the heart rate via the pulse sensor.
2. The microcontroller transmits this data to the Flutter app via Bluetooth.
3. The mobile app analyzes stress levels based on predefined thresholds.
4. Appropriate activities are enabled:
   - High Stress → Yoga, Breathing Exercises
   - Moderate Stress → Music Therapy, Art Therapy
   - Peaceful → Puzzle Solving, Spot the Difference

## 📊 Results Snapshot

| User | Heart Rate (BPM) | Stress Level Detected | Activity Recommended                 |
|------|------------------|-----------------------|--------------------------------------|
| 1    | 78               | Peaceful              | Puzzle Solving, Social Interaction   |
| 2    | 92               | Moderate Stress       | Music Therapy, Art Therapy           |
| 3    | 65               | Peaceful              | Puzzle Solving, Spot the Difference  |
| 4    | 109              | High Stress           | Yoga, Breathing Exercises            |

## 🧪 Tools & Technologies

### Hardware
- ESP32 Microcontroller
- Pulse Sensor
- Bluetooth Module

### Software
- Flutter (for mobile app UI)
- Arduino IDE (for microcontroller programming)
- **Render** – For hosting backend services and keeping the server running
- **Microsoft Azure** – Used for secure authentication and cloud-based data retrieval
## 📷 Demo & Screenshots

![wearable1](https://github.com/user-attachments/assets/40749b16-234c-421d-a672-cfbfbedfd056)
![wearable2](https://github.com/user-attachments/assets/cdd48b5f-f828-43f2-aa8b-846919d4886d)
![logins](https://github.com/user-attachments/assets/3f52f8fb-e077-46e5-92ba-ded43c4fc59b)
![home page1](https://github.com/user-attachments/assets/69b3ca25-17d6-419e-939f-dc25a30e328c)
![home page2](https://github.com/user-attachments/assets/e44d6c72-1ab1-43d3-89bf-5b498cfd233b)
![activities high](https://github.com/user-attachments/assets/b4b12b55-dbc3-43f9-bf1d-e67485aca5c4)
![activities moderate](https://github.com/user-attachments/assets/8645f6ed-f702-4fc7-9b8f-865fead61193)
![activities peace](https://github.com/user-attachments/assets/5a7f65d7-f56a-4284-bc04-9bd2dcdfa8ae)

## 🔗 Useful Links

- [Flutter](https://flutter.dev/)
- [ESP32 Documentation](https://docs.espressif.com/projects/esp-idf/en/latest/esp32/)
- [Microsoft Azure](https://azure.microsoft.com/)
- [Render](https://render.com/)

## 🤝 Contribution

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## 📝 License

This project is licensed under the MIT License 
