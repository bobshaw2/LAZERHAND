# LaserHands

An interactive, real-time computer vision project that turns your hands into a high-voltage laser show. Using MediaPipe and OpenCV, this script tracks your fingertips with ultra-high precision and strings vibrant, anti-aliased neon laser lines between your left and right hands with zero lag or motion blur.

## 🎥 Demo

Watch the project in action on LinkedIn:

🔗 https://www.linkedin.com/feed/update/urn:li:activity:7483940643912966144/

> If you enjoyed the project, feel free to like, comment, and connect!

---

## ✨ Features

- **Zero-Blur Precision:** Custom rendering pipeline using anti-aliased vectors (`cv2.LINE_AA`) for crisp, razor-sharp light beams instead of muddy overlays.
- **Handshake Tracking Lock:** Leverages MediaPipe's multi-handedness classification to ensure lasers **only** connect matching fingers from distinct Left and Right hands—no chaotic jumping or flickering.
- **White-Hot Core Contrast:** Mimics realistic high-energy lasers by layering a pure white inner core over vibrant neon outlines.
- **Real-time Performance:** Fully optimized loop designed to run smoothly at up to **60 FPS** on standard webcams.

---

## 🔌 Installation

Make sure Python is installed, then install the required dependencies:

```bash
pip install opencv-python mediapipe numpy
```

---

## 🚀 Usage

Connect your webcam and run:

```bash
python main.py
```

---

## 🎮 Controls

- 🖐️ Show both hands in front of the webcam to activate the laser strings.
- ❌ Press **Q** while the video window is focused to safely exit the application.

---

## 🎨 Laser Color Profile

Each finger shoots a unique high-intensity neon wavelength.

| Finger | Laser Color | BGR Value |
|---------|-------------|-----------|
| 👍 Thumb | 🌸 Pink / Magenta | `(255, 0, 128)` |
| ☝️ Index | 💎 Cyan / Aqua | `(255, 255, 0)` |
| 🖕 Middle | 🥦 Neon Green | `(0, 255, 0)` |
| 💍 Ring | 🍊 Bright Orange | `(255, 128, 0)` |
| 🤙 Pinky | 🍎 Pure Laser Red | `(0, 0, 255)` |

---

## 🛠 Built With

- Python
- OpenCV
- MediaPipe
- NumPy

---

## 📜 Acknowledgments

- **MediaPipe** for the lightning-fast hand landmark tracking models.
- **OpenCV** for the robust real-time image processing framework.

---

## ⭐ Support

If you found this project useful, consider giving the repository a ⭐ on GitHub. It helps others discover the project and motivates future improvements!
