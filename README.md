# AI-Powered Behaviour Detection System

## 📌 Overview
The AI-Powered Behaviour Detection System is a real-time computer vision-based application designed to monitor and analyze human behaviour using deep learning and image processing techniques.

The system uses YOLOv8 for real-time person and object detection, along with MediaPipe-based facial landmark analysis and head pose estimation to identify attention levels, distractions, and behavioural patterns.

This project can be applied in smart classrooms, online learning environments, workplace monitoring, and human behaviour analytics.

---

## 🎯 Problem Statement
Traditional monitoring systems require manual observation, which is time-consuming and inefficient. This project aims to develop an automated AI-based solution that can analyze real-time video feeds and detect behavioural patterns such as:

- Lack of attention
- Looking away from the screen
- Mobile phone usage
- Multiple person detection
- Distracted behaviour

---

## 🚀 Features

✅ Real-time video-based behaviour analysis  
✅ Person detection using YOLOv8  
✅ Mobile phone detection for distraction monitoring  
✅ Head pose estimation for attention analysis  
✅ Face landmark tracking using MediaPipe  
✅ Dynamic attention score calculation  
✅ Multi-person behaviour monitoring  
✅ Live visual feedback with bounding boxes and alerts  

---

## 🏗️ System Workflow

1. Capture real-time video input using webcam/video stream
2. Detect humans and objects using YOLOv8
3. Extract facial landmarks using MediaPipe
4. Perform head pose estimation
5. Analyze behaviour patterns
6. Calculate attention score based on detected activities
7. Display real-time monitoring results

---

## 🛠️ Technologies Used

### Programming Language
- Python

### Computer Vision
- OpenCV
- MediaPipe
- YOLOv8 (Ultralytics)

### Data Processing
- NumPy

### Development Tools
- VS Code
- Jupyter Notebook
- Git & GitHub

---

## 📂 Project Structure

```
behaviour_detection/
│
├── main.py                 # Main application file
├── debug_mp.py             # MediaPipe debugging/testing
├── requirements.txt        # Required Python packages
├── README.md               # Project documentation
│
└── models/
    └── yolov8_model.pt     # YOLO model weights
```

---

## ⚙️ Installation & Setup

### 1. Clone Repository

```bash
git clone https://github.com/yourusername/behaviour_detection.git
```

### 2. Navigate to Project Folder

```bash
cd behaviour_detection
```

### 3. Create Virtual Environment

```bash
python -m venv venv
```

### 4. Activate Environment

Windows:

```bash
venv\Scripts\activate
```

Linux/Mac:

```bash
source venv/bin/activate
```

### 5. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Project

Run:

```bash
python main.py
```

The webcam will start capturing video and display real-time behaviour detection results.

---

## 📊 Detection Logic

The system assigns attention levels based on:

| Behaviour | Impact |
|---|---|
| Face looking forward | Positive attention |
| Looking away | Attention decrease |
| Mobile phone detected | Distraction detected |
| No face detected | Reduced attention |

---

## 📸 Demo

(Add screenshots/GIF/video demonstration here)

Example:

```
![Demo](images/demo.png)
```

---

## 🔮 Future Improvements

- Add emotion recognition
- Improve detection accuracy using custom-trained datasets
- Cloud-based monitoring dashboard
- Store analytics reports in database
- Deploy as a web application
- Add multiple classroom support

---

## 👩‍💻 Author

**Sreya P P**

Computer Science Graduate | AI & Machine Learning Enthusiast

# AI-Powered Behaviour Detection System

## 📌 Overview
The AI-Powered Behaviour Detection System is a real-time computer vision-based application designed to monitor and analyze human behaviour using deep learning and image processing techniques.

The system uses YOLOv8 for real-time person and object detection, along with MediaPipe-based facial landmark analysis and head pose estimation to identify attention levels, distractions, and behavioural patterns.

This project can be applied in smart classrooms, online learning environments, workplace monitoring, and human behaviour analytics.

---

## 🎯 Problem Statement
Traditional monitoring systems require manual observation, which is time-consuming and inefficient. This project aims to develop an automated AI-based solution that can analyze real-time video feeds and detect behavioural patterns such as:

- Lack of attention
- Looking away from the screen
- Mobile phone usage
- Multiple person detection
- Distracted behaviour

---

## 🚀 Features

✅ Real-time video-based behaviour analysis  
✅ Person detection using YOLOv8  
✅ Mobile phone detection for distraction monitoring  
✅ Head pose estimation for attention analysis  
✅ Face landmark tracking using MediaPipe  
✅ Dynamic attention score calculation  
✅ Multi-person behaviour monitoring  
✅ Live visual feedback with bounding boxes and alerts  

---

## 🏗️ System Workflow

1. Capture real-time video input using webcam/video stream
2. Detect humans and objects using YOLOv8
3. Extract facial landmarks using MediaPipe
4. Perform head pose estimation
5. Analyze behaviour patterns
6. Calculate attention score based on detected activities
7. Display real-time monitoring results

---

## 🛠️ Technologies Used

### Programming Language
- Python

### Computer Vision
- OpenCV
- MediaPipe
- YOLOv8 (Ultralytics)

### Data Processing
- NumPy

### Development Tools
- VS Code
- Jupyter Notebook
- Git & GitHub

---

## 📂 Project Structure

```
behaviour_detection/
│
├── main.py                 # Main application file
├── debug_mp.py             # MediaPipe debugging/testing
├── requirements.txt        # Required Python packages
├── README.md               # Project documentation
│
└── models/
    └── yolov8_model.pt     # YOLO model weights
```

---

## ⚙️ Installation & Setup

### 1. Clone Repository

```bash
git clone https://github.com/yourusername/behaviour_detection.git
```

### 2. Navigate to Project Folder

```bash
cd behaviour_detection
```

### 3. Create Virtual Environment

```bash
python -m venv venv
```

### 4. Activate Environment

Windows:

```bash
venv\Scripts\activate
```

Linux/Mac:

```bash
source venv/bin/activate
```

### 5. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Project

Run:

```bash
python main.py
```

The webcam will start capturing video and display real-time behaviour detection results.

---

## 📊 Detection Logic

The system assigns attention levels based on:

| Behaviour | Impact |
|---|---|
| Face looking forward | Positive attention |
| Looking away | Attention decrease |
| Mobile phone detected | Distraction detected |
| No face detected | Reduced attention |

---

## 📸 Demo

(Add screenshots/GIF/video demonstration here)

Example:

```
![Demo](images/demo.png)
```

---

## 🔮 Future Improvements

- Add emotion recognition
- Improve detection accuracy using custom-trained datasets
- Cloud-based monitoring dashboard
- Store analytics reports in database
- Deploy as a web application
- Add multiple classroom support

---

## 👩‍💻 Author

**Sreya P P**

Computer Science Graduate | AI & Machine Learning Enthusiast

LinkedIn:www.linkedin.com/in/sreya-p-p


---

## ⭐ Acknowledgements

- Ultralytics YOLO
- Google MediaPipe
- OpenCV Community

---

## ⭐ Acknowledgements

- Ultralytics YOLO
- Google MediaPipe
- OpenCV Community
