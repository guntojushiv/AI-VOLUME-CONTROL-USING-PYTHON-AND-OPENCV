# AI Volume Control Using Python and OpenCV

## 🎯 **Project Overview**
This project implements an AI-based volume control system using hand gestures. By leveraging **Python**, **OpenCV**, and **MediaPipe**, the system detects hand landmarks, measures the distance between fingers, and maps that distance to control the system's volume.

## 🛠️ **Technologies Used**

- **Python**: A versatile, high-level programming language used to write the logic of the application.
- **OpenCV**: An open-source computer vision library that helps with image and video processing.
- **MediaPipe**: A framework by Google that provides pre-built ML solutions, including hand tracking, face detection, and more.

---

## 📂 **Project Structure**
```
├── AI VOLUME CONTROL HAND GESTURES PROJECT/
│   ├── volume_control.py         # Main Python script
│   ├── HandTrackingModule.py    # Module to track hand landmarks
│   ├── README.md                # Project documentation
│   ├── requirements.txt         # List of dependencies
└─── └── media/                  # Folder for demo videos or images
```

---

## ⚡ **Features**

- **Real-time Hand Tracking**: Detect hand and finger landmarks using MediaPipe.
- **Distance Calculation**: Measure the distance between the thumb and index finger.
- **Volume Control**: Map finger distance to system volume using the `pycaw` library.
- **Visual Feedback**: Display a live video feed with a volume bar and percentage overlay.

---

## 🚀 **Installation & Setup**

1. **Clone the Repository:**
```bash
git clone https://github.com/guntojushiv/AI-VOLUME-CONTROL-USING-PYTHON-AND-OPENCV.git
cd AI-VOLUME-CONTROL-USING-PYTHON-AND-OPENCV
```

2. **Create a Virtual Environment (Optional but Recommended):**
```bash
python -m venv venv
source venv/bin/activate   # For macOS/Linux
venv\Scripts\activate     # For Windows
```

3. **Install Required Packages:**
```bash
pip install -r requirements.txt
```

> **requirements.txt:**
```
opencv-python
mediapipe
comtypes
pycaw
numpy
```

---

## 🟩 **How the Code Works**

1. **Hand Detection with MediaPipe:**
   - The **HandTrackingModule** uses MediaPipe to detect hand landmarks.

2. **Distance Calculation:**
   - The Euclidean distance between the thumb and index finger is calculated.

3. **Volume Adjustment:**
   - The distance is mapped to volume levels using the **pycaw** library.

4. **UI with OpenCV:**
   - A live video feed with an interactive volume bar is shown using OpenCV.

---

## ▶️ **Running the Project**

Simply run the Python script:
```bash
python volume_control.py
```

The webcam will start, and you can control the volume by bringing your thumb and index finger closer or farther apart.

---

## ✅ **Demo**

You can add a demo video or GIF showing the project in action!

---

## 📘 **Explanation of Key Libraries**

- **Python:**
   - A powerful, beginner-friendly language widely used for AI, ML, and computer vision.

- **OpenCV:**
   - Provides easy tools for image processing, drawing shapes, and capturing video streams.

- **MediaPipe:**
   - Simplifies hand and pose detection with pre-trained ML models.

- **pycaw:**
   - A library to interact with Windows' audio settings and control volume programmatically.

---

## 🛠️ **Troubleshooting**

- **Camera Not Working:** Ensure your webcam is connected and accessible.
- **ModuleNotFoundError:** Double-check that all packages are installed.
- **Permission Issues (Mac/Linux):** Grant camera permissions if needed.

---

## 📜 **Conclusion**

This project is a great introduction to real-time hand tracking and gesture control using Python and computer vision libraries. You can enhance it by adding more gestures or integrating it with other smart home devices!

If you found this useful, feel free to give the repo a ⭐ on GitHub!

---

## 📧 **Contact**

🔗 GitHub: [guntojushiv](https://github.com/guntojushiv)
