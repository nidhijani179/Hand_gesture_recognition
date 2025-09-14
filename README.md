<img width="610" alt="image" src="https://github.com/user-attachments/assets/9351fa41-4a53-4265-b7f1-02829f2c6c0d">

![image](https://github.com/user-attachments/assets/d720ed1c-28aa-4380-96a5-50d074e14ce9)
<img width="611" alt="image" src="https://github.com/user-attachments/assets/04b85569-fcbe-400c-aea8-50598af5c443">

# ✋ Hand Gesture Recognition for Virtual Presentations  

This project is an interactive **hand gesture recognition system** that enables **touch-free control of presentations**.  
Using **computer vision** and **machine learning (MediaPipe)**, the system recognizes hand gestures in real time to switch slides, annotate, and interact with on-screen content.  

  

---

## 🚀 Features  
- 🖐️ **Hand Detection & Tracking** (MediaPipe)  
- 👉 **Gesture Recognition** (raised fingers, pinch, distances)  
- 📑 **Slide Control** (next/previous using gestures)  
- ✏️ **On-Screen Annotation** (virtual pen drawing)  
- ➖ **Dotted Shapes** for styled annotations  

---

## 📂 Project Structure  
Hand_gesture_recognition-main/
│── HandTracker.py # Hand detection & gesture recognition
│── dottedline.py # Drawing utilities (dotted lines, rectangles)
│── main.py # Main application (presentation control)
│── Images/ # Slide images for the presentation
│── hand gesture.mp4 # Demo video
│── README.md # Documentation


---

## 🛠️ Tech Stack  
- Python 3.8+  
- OpenCV → Image processing & display  
- MediaPipe → Real-time hand landmark detection  
- NumPy → Numerical operations  

---

## ⚙️ Installation & Usage  

### 1️⃣ Clone Repository  
```bash
git clone https://github.com/yourusername/Hand_gesture_recognition.git
cd Hand_gesture_recognition-main

2️⃣ Install Dependencies
pip install opencv-python mediapipe numpy

3️⃣ Run the Application
python main.py


Make sure you have a webcam connected and an Images/ folder with slide images.

🎮 Gesture Controls

👉 Swipe Right Hand → Next Slide

👈 Swipe Left Hand → Previous Slide

✏️ Pinch & Drag → Draw annotations

✋ Five Fingers Up → Clear annotations

📖 Applications

🏫 Touch-free classroom presentations

♿ Assistive technology for contactless interaction

💻 Smart gesture-based interfaces



