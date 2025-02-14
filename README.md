# Vehicle Detection, Tracking, and Speed Estimation

##  Project Overview
This project implements a **Vehicle Speed Tracking System** that detects cars on a highway, tracks their movement, and estimates their speed over time. If a vehicle exceeds the predefined speed limit, the system highlights it with a red bounding box to indicate a violation.

##  Background
Predicting and monitoring vehicle speed is crucial for preventing road accidents. According to the **World Health Organization (WHO)**, approximately **1.3 million people** die each year due to road traffic crashes. Speeding is one of the leading causes of these accidents, making speed detection a vital component of road safety systems.

This project utilizes **YOLOv8** for vehicle detection and **DeepSORT** for object tracking. The speed estimation is done by measuring the pixel displacement of vehicles across frames and converting it into real-world speed using a calibration factor.

🔗 **Original Video Source**: [Pixabay - Roads & Motorways](https://pixabay.com/videos/roads-motorways-highway-1952/)

##  Features
- **Real-time Vehicle Detection** using **YOLOv8**
- **Multi-object Tracking** with **DeepSORT**
- **Speed Estimation** based on pixel displacement and calibration
- **Speed Limit Alert**: Vehicles exceeding the speed limit are highlighted in red
- **Video Processing & Output Generation**

##  Technologies Used
- **Python**
- **YOLOv8 (Ultralytics)** for object detection
- **DeepSORT** for multi-object tracking
- **OpenCV** for video processing
- **NumPy & Math** for speed calculations

## 📂 Project Structure
```
📂 Vehicle-Speed-Tracking
│── results/                # Processed video output
│── highway_video.mp4       # Input video file
│── vehicle_speed_tracking.ipynb  # Main Google Colab notebook
│── README.md               # Project documentation
```

##  Installation & Setup
To run this project in **Google Colab** or a local environment, follow these steps:

### 1️⃣ Install Dependencies
```bash
pip install ultralytics deep-sort-realtime opencv-python-headless
```

### 2️⃣ Clone the Repository
```bash
git clone https://github.com/NeginHz/Vehicle-Detection-Tracking-and-Speed-Estimation
cd Vehicle-Speed-Tracking
```

### 3️⃣ Run the Notebook
Open `vehicle_speed_tracking.ipynb` in **Google Colab** and run all cells.

## 🎥 Demo Output
You can watch the output video at the following link:
[🔗 YouTube Result](https://www.youtube.com/watch?v=QpQxzGtMqsk)

##  Future Improvements
- Improve **speed calibration** using real-world data
- Experiment with **different tracking algorithms** (e.g., ByteTrack, SORT)
- Implement **automatic license plate recognition (ALPR)** for vehicle identification

## 📜 References
- **World Health Organization (2022)** - [Road Traffic Injuries](https://www.who.int/news-room/fact-sheets/detail/road-traffic-injuries)
- **Ultralytics YOLOv8** - [Documentation](https://docs.ultralytics.com/)
- **DeepSORT Tracker** - [GitHub Repo](https://github.com/nwojke/deep_sort)

---
👨‍💻 Developed by Negin Hezarjaribi - 2025 🚀

