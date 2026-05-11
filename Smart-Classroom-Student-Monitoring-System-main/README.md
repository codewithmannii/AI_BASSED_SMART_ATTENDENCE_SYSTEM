# 🎓 AI-Powered Smart Attendance Monitoring

An AI-based Smart Classroom Monitoring System that automates attendance and analyzes student behavior in real time using Computer Vision and Deep Learning techniques. The system tracks hand raise activity, student attention, body posture, and facial emotions using OpenCV, MediaPipe, and TensorFlow.

---

## 🚀 Features

### 📌 Hand Raise Detection

* Detects raised hands in real time using MediaPipe Hands.
* Recognizes students using face recognition techniques.
* Automatically records participation status in Excel.

### 📌 Head Position & Attention Monitoring

* Tracks student head position and posture.
* Determines whether the student is attentive or distracted.
* Uses MediaPipe Pose for landmark detection.

### 📌 Emotion Detection

* Detects facial emotions using a pre-trained CNN model.
* Supports real-time emotion analysis through webcam input.
* Emotion logs are stored automatically.

### 📌 Automated Attendance System

* Recognizes students using stored face images.
* Prevents proxy attendance through facial verification.
* Stores attendance data in Excel files.

---

## 🛠️ Technologies Used

* Python
* OpenCV
* MediaPipe
* TensorFlow / Keras
* NumPy
* Pandas
* OpenPyXL

---

## 📂 Project Structure

```bash
AI-Powered-Smart-Attendance-Monitoring/
│
├── HandRaiseDetection.py
├── emotion.py
├── headposition.py
├── BodyLanguageAnalysis.py
├── student image/
├── emotion_detection_model.h5
├── attendance.xlsx
├── emotion_attendance.xlsx
├── attention.xlsx
└── student_attendance.xlsx
```

---

## ⚙️ Installation

### 1️⃣ Clone Repository

```bash
git clone https://github.com/codewithmannii/AI_BASSED_SMART_ATTENDENCE_SYSTEM.git
```

### 2️⃣ Navigate to Project Folder

```bash
cd AI_BASSED_SMART_ATTENDENCE_SYSTEM
```

### 3️⃣ Create Virtual Environment

```bash
python -m venv venv
```

### 4️⃣ Activate Virtual Environment

#### Windows

```bash
venv\Scripts\activate
```

### 5️⃣ Install Dependencies

```bash
pip install opencv-python mediapipe tensorflow pandas openpyxl numpy
```

---

## ▶️ How to Run

### Hand Raise Detection

```bash
python HandRaiseDetection.py
```

### Emotion Detection

```bash
python emotion.py
```

### Head Position Detection

```bash
python headposition.py
```

### Body Language Analysis

```bash
python BodyLanguageAnalysis.py
```

Press `q` to stop the webcam.

---

## 🖼️ Student Images

Store student images inside the `student image` folder.

Example:

```bash
student image/
   mayank.jpg
   rahul.jpg
```

---

## 📊 Output

The system automatically generates Excel files such as:

* `attendance.xlsx`
* `emotion_attendance.xlsx`
* `attention.xlsx`
* `student_attendance.xlsx`

These files contain attendance and behavioral analysis logs.

---

## 🎯 Use Cases

* Smart Classroom Monitoring
* Automated Attendance Tracking
* Student Engagement Analysis
* AI-Based Behavior Monitoring
* Real-Time Classroom Analytics

---

## 🔮 Future Improvements

* Cloud Database Integration
* Web Dashboard for Analytics
* Multi-Classroom Support
* Improved AI Accuracy
* Mobile App Integration

---

## 👨‍💻 Author

### Mayank Gandhi

📧 Email: [mayankgandhi1114@gmail.com](mailto:mayankgandhi1114@gmail.com)

🔗 LinkedIn: https://www.linkedin.com/in/mayank-gandhi-01b87a251/

💻 GitHub: https://github.com/codewithmannii

---

