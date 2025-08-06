# 🎨 AirArt — Draw with Your Hands Using Computer Vision

AirArt is an innovative computer vision-based web app that lets you draw in the air using only **hand gestures** — no stylus, no touchscreen. It uses **MediaPipe** and **OpenCV** to detect hand landmarks and finger movement, translating them into brush strokes on a digital canvas in real time. AirArt is responsive and accessible on all major devices.

---

## 🌐 Live Demo

[🔗 View Project](https://airart.onrender.com)

---

## 🚀 Project Goal

The aim of this project is to:
- Explore natural interaction between humans and machines.
- Allow users to create digital art without physical contact.
- Apply computer vision and hand-tracking techniques in an intuitive application.

---

## 🔧 How It Works

1. The webcam captures real-time video input.
2. MediaPipe detects hand landmarks and tracks index finger movement.
3. OpenCV renders the finger movement as drawings on the screen.
4. Users can select colors, clear the canvas, or save their art using hand gestures mapped to virtual buttons.

---

## 🖥️ Tech Stack

- **Python 3.9**
- **Flask** (Web backend)
- **OpenCV** (Video processing and drawing)
- **MediaPipe** (Hand landmark detection)
- **NumPy**
- **HTML + CSS + JS** (Frontend interface)

---

## ✨ Key Features

- 🖐️ Draw with index finger in mid-air
- 🎨 Switch between multiple brush colors
- 🗑️ Clear canvas with gesture
- 💾 Save your drawing as an image
- ⚡ Real-time hand detection using MediaPipe

---

## 📸 Screenshots

<img width="1918" height="917" alt="image" src="https://github.com/user-attachments/assets/884d10db-cc8e-4ee5-897c-1bcebd3277cf" />


---

## 📁 Project Structure
```
AirArt/
│
├── app.py # Flask app runner
├── Aircanvas.py # Main drawing logic using OpenCV & MediaPipe
├── camera_app.py # Handles webcam stream
├── templates/
│ └── index.html # Frontend UI
├── static/
│ ├── styles.css
│ └── images, assets
├── requirements.txt
└── README.md
```

---

### ⚠️ Deployment Note
This is a **real-time, camera-based desktop app** and **cannot be deployed on cloud services like Render** due to:
- No access to webcam hardware on server
- No GUI display for `cv2.imshow()`

### 🚀 How to Run Locally

```bash
# Clone the repo
git clone https://github.com/i-am-ap/AirArt.git
cd AirArt

# Create virtual environment
python -m venv venv
venv\Scripts\activate    # or source venv/bin/activate (Linux/Mac)

# Install dependencies
pip install -r requirements.txt

# Run the app
python app.py
```
---

## 🧠 Learnings

- How to integrate MediaPipe into real-time applications.
- Building intuitive gesture-based interaction interfaces.
- Bridging computer vision with web deployment.

---

## 🤝 Acknowledgments

This project is a part of academic exploration and experimentation in **gesture-controlled applications**.

The Project is created by Aryan Palaspagar.

