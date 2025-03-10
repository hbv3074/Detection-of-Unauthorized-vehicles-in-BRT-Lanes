# 🚗 Detection of Unauthorized Vehicles in BRT Lanes  

## 📌 Overview  
This project aims to build a system that detects **unauthorized vehicles** in **Bus Rapid Transit (BRT) lanes** using **YOLOv8**, **Computer Vision**, and **Optical Character Recognition (OCR)**. The system identifies vehicles, extracts their license plate numbers, and cross-references them with a database of permitted vehicles. Unauthorized vehicles are flagged for further action.

📄 **A research paper based on this project has been published.**  
[🔗 Read it here](https://ieeexplore.ieee.org/document/10895734/authors).

## ✨ Features  
✅ **Real-time License Plate Detection** with YOLOv8  
✅ **OCR-Based Plate Extraction** using EasyOCR  
✅ **Database Cross-Verification** to identify unauthorized vehicles  
✅ **Automated Flagging of Blacklisted Vehicles**  

## 🛠️ Technology Stack  
- **YOLOv8** – Object detection for vehicles and license plates  
- **EasyOCR** – Extracting text from detected license plates  
- **OpenCV** – Image processing and enhancement  
- **Python** – Backend development and automation  

## 📂 Project Workflow  
1️⃣ **Vehicle & License Plate Detection** → YOLOv8 detects vehicles and license plates in BRT lanes  
2️⃣ **License Plate Text Extraction** → EasyOCR extracts the plate number  
3️⃣ **Database Cross-Checking** → The extracted plate number is matched against an authorized vehicle database  
4️⃣ **Unauthorized Vehicle Flagging** → Blacklisted vehicles are identified and logged  

## 🚀 Performance Evaluation  
- **Accuracy** of license plate detection and extraction  
- **Success rate** of identifying blacklisted vehicles  
- **Efficiency** of real-time processing  

## 📸 Sample Output  

Below are the sample outputs of the **Unauthorized Vehicle Detection System in BRT Lanes**:

🔍 **License Plate Detection UI**  
The system detects and verifies license plates from a video input.  
![License Plate Detector UI](Screenshot%202025-03-10%20170919.png)

📋 **Authorized Vehicles Database**  
The CSV file contains **authorized license plate numbers** allowed in the BRT lane.  
![Authorized Vehicles Database](Screenshot%202025-03-10%20170924.png)

🚫 **Unauthorized Vehicles Log**  
The system stores unauthorized vehicle **Car ID and License Number** in a separate CSV file.  
![Unauthorized Vehicles Log](Screenshot%202025-03-10%20170927.png)
  


## 🏗️ Future Enhancements  
🔹 Integration with **live CCTV feeds** for real-time tracking  
🔹 Deployment on **edge devices** for faster processing  
🔹 Development of a **dashboard for analytics and reporting**  

## 🤝 Contributors  
🚀 **Harsh Balkrishna Vahal**  
[![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/hbv3074)  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/harsh-vahal/)
