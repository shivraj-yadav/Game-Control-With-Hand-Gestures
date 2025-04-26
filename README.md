# 🖐️ Game Control with Hand Gestures

Control PC games using your hand gestures via webcam! This project uses **OpenCV**, **MediaPipe**, **NumPy**, and **ctypes** to translate hand movements into keyboard inputs (W, A, S, D, and Space), allowing you to play games without touching the keyboard.

## 🚀 Features

- Real-time hand tracking using webcam input
- Gesture recognition for directional controls and actions
- Keyboard simulation for W, A, S, D, and Space keys
- Compatible with any keyboard-controlled games including:
  - Racing games (Asphalt 8)
  - Platformers (Run 3)
  - Vehicle simulators (Unity Car Games)
  - Online games (Slope Game, Moto X3M)

## 🛠️ Built With

- Python 3.7+
- OpenCV - Computer vision processing
- MediaPipe - Hand tracking and landmark detection
- NumPy - Mathematical operations
- ctypes - Windows key simulation

## 📥 Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/shivraj-yadav/Game-Control-With-Hand-Gestures.git
   cd Game-Control-With-Hand-Gestures
   ```

2. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Controller**
   ```bash
   python hand_gesture_controller.py
   ```

4. Open your favorite keyboard-controlled game and start playing!

## 🎮 Recommended Games for Testing

- Slope Game
- Moto X3M
- Run 3
- Temple Run 2 Online
- Any racing game with WASD controls

## ✨ How It Works

1. **Capture**: OpenCV accesses webcam feed in real-time
2. **Detection**: MediaPipe identifies and tracks hand landmarks
3. **Analysis**: Hand position and movement are calculated through vector math
4. **Simulation**: Based on detected gestures, corresponding keyboard inputs are triggered via ctypes
5. **Response**: Games receive keyboard inputs and respond accordingly

## 🧩 Project Structure

```
Game-Control-With-Hand-Gestures/
│
├── hand_gesture_controller.py  # Main script for webcam input and gesture control
├── inputkey.py                 # Key simulation utilities
├── README.md                   # Project documentation
├── requirements.txt            # Python dependencies
└── .gitignore                  # Git ignore configuration
```

## 📄 System Requirements

- Python 3.7 or higher
- Windows OS (required for ctypes.windll.user32.SendInput)
- Webcam with clear view of your hands
- Sufficient lighting for hand detection


## 🙋‍♂️ Author

**Shivraj Ravindra Yadav**  
[GitHub](https://github.com/shivraj-yadav) | [LinkedIn](https://www.linkedin.com/in/shivraj-yadav/)


## ⭐ Show Your Support

If you find this project useful, please consider giving it a star on GitHub!
