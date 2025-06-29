# Media_Pipe

This repository demonstrates the use of [MediaPipe](https://mediapipe.dev/) for real-time detection and tracking of human features including hands, face, and body pose. It includes implementations for:

- Hand Detection
- Face Detection
- Face Mesh
- Pose Estimation

## 📁 Contents

### 🔍 Detection Modules
Each module uses MediaPipe's pre-trained models:
- `hand_detection.ipynb` – Detects and tracks hand landmarks
- `face_detection.ipynb` – Detects faces in real-time
- `face_mesh.ipynb` – Generates detailed face landmark mesh
- `pose_detection.ipynb` – Estimates full-body pose

### 🧠 Projects

#### ✋ Finger Count
Detects the number of fingers raised in front of the webcam using MediaPipe Hand landmarks.

- **Input**: Real-time video feed
- **Output**: Number of fingers shown (0–5)

#### 🤙 Gesture Recognition
Classifies hand gestures using the hand landmarks and simple geometric rules.

- **Recognized Gestures**:
  - Thumbs Up 👍
  - Thumbs Down 👎
  - Peace ✌️
  - I Love You 🤟
  - Stop ✋
  - OK Sign 👌

## ⚙️ Requirements

- Python 3.7+
- OpenCV
- MediaPipe

