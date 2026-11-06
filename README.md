# 🖐️ AI-Powered Multi-User Gesture Control & Authentication System

An advanced, intelligent desktop application that integrates secure multi-factor authentication and hands-free OS control using custom deep learning models. The system authenticates users via traditional passwords combined with hand gesture verification codes, and enables real-time system operations (volume, brightness, and window management) through computer vision and machine learning.

---

## 🚀 Key Features

* **Secure Multi-User Authentication:** A robust login mechanism requiring standard credentials plus a dynamic verification code derived from specific hand gesture images.
* **Dual AI Model Integration:** Utilizes two specialized deep learning models trained to classify precise hand gesture inputs for authentication and system commands.
* **Gesture-Based OS Control:** Once authenticated, users can seamlessly control core operating system features hands-free:
  * Adjust system volume.
  * Control screen brightness.
  * Open, close, and manage active desktop windows.
* **Real-Time Processing Pipeline:** Actively transitioning from static image inputs to live, streaming webcam feeds for seamless real-time interaction using OpenCV and MediaPipe.

---

## 📂 Project Architecture & Directory Structure

```text
ai-gesture-system/
│
├── data/                  # Sample datasets and gesture image references
├── models/                # Trained model files (.keras / .pkl) and weights
├── src/                   # Core application scripts
│   ├── auth.py            # Multi-user authentication & gesture verification logic
│   ├── control.py         # OS control modules (volume, brightness, windows)
│   └── train_models.py    # Scripts used to train the deep learning models
│
├── app.py                 # Main application entry point (GUI/Desktop interface)
├── requirements.txt       # Project dependencies and Python libraries
└── README.md              # Project documentation
