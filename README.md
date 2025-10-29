# 💤 Eye Blink & Drowsiness Detection for Driver Safety

A real-time driver alertness monitoring system that uses computer vision and deep learning to detect signs of fatigue.  
This project is designed to enhance road safety by issuing early warnings when drivers show symptoms of drowsiness or inattention.

---

## 🚀 Key Features

- **🧠 Data Collection:**  
  Curated and preprocessed a dataset of **7,000 facial expression images**, representing various levels of driver fatigue.

- **🔍 Feature Extraction:**  
  Extracted important visual cues such as **eye blink frequency**, **mouth openness**, and **head movement** to evaluate driver alertness.

- **🤖 Machine Learning Model:**  
  Developed and trained a **Convolutional Neural Network (CNN)** to accurately classify driver states as *alert* or *drowsy*.

- **🎥 Real-Time Detection:**  
  Integrated the trained CNN into a **live monitoring system** that continuously analyzes video input from an in-vehicle camera.

- **⚡ Optimized Performance:**  
  Minimized system latency and optimized processing speed to ensure **instantaneous detection and alerts**.

- **🧪 Testing & Validation:**  
  Conducted rigorous testing across multiple **lighting, posture, and motion conditions** to ensure reliability and accuracy.

---

## 🧩 Technologies Used

- **Programming Language:** Python  
- **Libraries & Tools:** OpenCV, Dlib / Mediapipe, NumPy, Pandas, TensorFlow / PyTorch, Matplotlib  

---

## ⚙️ How It Works

1. **Face Detection:** The system identifies the driver’s face in real time using OpenCV or Mediapipe.  
2. **Feature Extraction:** Computes metrics like **Eye Aspect Ratio (EAR)** and **Mouth Aspect Ratio (MAR)** from facial landmarks.  
3. **Classification:** The CNN model predicts whether the driver is **alert** or **drowsy**.  
4. **Alert Mechanism:** When drowsiness is detected, the system triggers an **audio or visual alert** to wake the driver.

---

## 📈 Results

- Achieved **high accuracy** in detecting drowsiness under real-world conditions.  
- Maintained **low latency** (<100ms per frame) for seamless real-time performance.  
- Effectively differentiates between normal blinking and prolonged eye closure.

---

## 🔮 Future Enhancements

- Integration with **IoT-enabled vehicle systems** for automatic intervention (e.g., slowing the vehicle).  
- Development of a **cloud dashboard** for driver behavior monitoring and reporting.  
- Incorporation of **physiological sensors** (e.g., heart rate, pulse) for multimodal fatigue detection.

---

