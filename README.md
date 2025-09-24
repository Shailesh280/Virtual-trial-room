# Virtual Trial Room 👕👗

A real-time **Virtual Trial Room** using **CNNs, OpenCV, Mediapipe, and Tkinter**.  
This project lets users "try on" shirts virtually using a webcam feed, deep learning classification, and pose detection.

---

## ✨ Features
- Train a CNN on the **Fashion MNIST dataset** for clothing classification  
- Detect user pose (shoulders, hips) using **Mediapipe Pose**  
- Overlay shirt images realistically on webcam feed  
- Switch between shirt styles using **hand gestures**  
- User-friendly **Tkinter GUI** with male/female selection  

---

## 📂 Repository Structure
```
/
├── MLModel.py               # CNN training on Fashion MNIST (saves xyz.h5 model)
├── Virtual trial room.py    # Main GUI + virtual try-on application
├── Shirts                  # Sample shirt images with transparent background
└── README.md                # Documentation
```

---

## ⚙️ Installation

1. Clone the repo:
   ```bash
   git clone https://github.com/Shailesh280/Virtual-trial-room.git
   cd Virtual-trial-room
   ```
   

2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. **Workflow**:
   - Launch app → Select gender (male/female)  
   - Webcam feed opens  
   - Pose detection aligns shirt on shoulders  
   - Switch shirts with **hand gesture detection**  
   - Press **`q`** to exit  

---

## 📦 Requirements

See [`requirements.txt`](./requirements.txt).

---

## 🚀 Future Improvements
- Extend to full outfits (pants, coats, dresses)  
- Add support for multiple poses and occlusions  
- Deploy as a web/AR app  
- Improve fitting realism with body segmentation  

---

