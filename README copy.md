# SenseWay v3.0

SenseWay is an assistive technology tool designed to empower users with limited motor control (e.g., ALS, Parkinson's) to interact with their computer using only eye movements and blinks.

## 🚀 Features

### 👁️ Gaze Control
- **Hands-Free Navigation**: Move the mouse cursor by looking at the screen.
- **Dynamic Smoothing**: Intelligent cursor stabilization filters out tremors and jitter while keeping movement responsive.
- **Adjustable Speed**: Configure cursor responsiveness from very slow (accessible) to fast.
- **Safe Zone Scope**: Optional setting to restrict cursor movement to a comfortable central area.

### 😉 Blink Interaction
- **Intentional Clicking**: Uses time-based blink detection (hold for ~150ms) to distinguish intentional clicks from natural blinks.
- **Anti-Fatigue**: Adjustable sensitivity thresholds reduce eye strain.
- **Visual Feedback**: Clear on-screen indicators when a blink is registered.

### 🛡️ Safety & Emergency
- **SOS Actions**: Quickly dial emergency contacts or send WhatsApp alerts.
- **Accidental Prevention**: "Arm & Confirm" logic prevents accidental emergency calls.
- **Configurable**: Set your emergency contact number directly in the settings UI.

### 💻 User Interface
- **High Contrast**: Dark-themed UI designed for visibility and low eye strain.
- **Assistive Keyboard**: Large, spaced keys for easier gaze typing.
- **Action Deck**: Quick access to Google, YouTube, and emergency tools.

## 🛠️ Installation

1. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
   *Note: Requires a webcam.*

2. **Run the Application**:
   ```bash
   python main.py
   ```

3. **Open the Interface**:
   The application should automatically open in your default browser at `http://127.0.0.1:5000`.

## ⚙️ Configuration

Click the **⚙ CONFIG** button in the top-right corner to:
- Set your **Emergency Contact Number**.
- Adjust **Blink Sensitivity** (Lower = Harder, Higher = Easier).
- Change **Cursor Speed** (0.3 = Very Slow, 1.5 = Fast).
- Change **Cursor Scope** (Full Screen vs. Comfortable Center).

## 📝 Usage Tips

- **Calibration**: Ensure you are well-lit and facing the camera directly.
- **Clicking**: Close your **Left Eye** firmly for a fraction of a second to click.
- **Resting**: If you need a break, look away from the screen or close the application tab.

## 📜 License
Open Source. Built for HackTU.