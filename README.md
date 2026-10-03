# 🎨 Air-Board: Computer Vision Virtual Air Writing Canvas

[![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)](https://opencv.org/)
[![MediaPipe](https://img.shields.io/badge/MediaPipe-00979D?style=for-the-badge&logo=google&logoColor=white)](https://mediapipe.dev/)
[![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org/)

**Air-Board** is an interactive computer vision application that turns hand gestures into a digital drawing board. Using real-time video feed processing, object/hand tracking algorithms, and gesture recognition, users can draw, write text, switch colors, and erase on a virtual canvas directly in mid-air using fingertip movements.

---

## ✨ Features

- 🖐️ **Real-Time Hand & Finger Tracking**: Tracks fingertip coordinates (Index Finger Tip landmark) with minimal latency using computer vision.
- 🎨 **Air Drawing & Painting Canvas**: Draw continuous lines, geometric shapes, or handwritten notes mid-air without touch input.
- 🌈 **Color Palette Selection**: Switch dynamically between multiple drawing colors (e.g., Red, Blue, Green, Yellow) using finger gesture modes.
- 🧹 **Eraser & Clear Canvas**: Select the virtual eraser mode or clear the entire screen with gesture controls.
- 📹 **Live WebCam Feed Integration**: Works with integrated laptop webcams or external USB cameras.

---

## 🚀 Getting Started

### Prerequisites

Ensure Python 3.8+ is installed along with the required computer vision libraries:

```bash
pip install opencv-python mediapipe numpy
```

### Running the Application

1. Clone the repository:
   ```bash
   git clone https://github.com/B-LIPIKA/Air-Board.git
   cd Air-Board
   ```

2. Execute the air-board application:
   ```bash
   python new_device.py
   ```

3. Position your hand in front of the camera:
   - **Index Finger Up**: Draw / Write on the air canvas.
   - **Index & Middle Fingers Up**: Selection Mode / Color Picker.
   - **All Fingers Up**: Clear Canvas / Erase.
   - **Press 'q'**: Quit application.

---

## 🛠️ Tech Stack & Dependencies

- **Language**: Python 3
- **Computer Vision**: `OpenCV` (`cv2`)
- **Hand Landmark Estimation**: `Google MediaPipe`
- **Matrix & Array Processing**: `NumPy`

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for details.
