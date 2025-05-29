

```markdown
# 🖐️🎤 Gesture and Voice-Controlled Application

This Python-based project combines computer vision and voice recognition to allow users to control various system functions using **hand gestures** and **voice commands**. It uses **MediaPipe** for hand tracking, **SpeechRecognition** for capturing voice commands, and **PyAutoGUI** for simulating keyboard and mouse actions.

---

## ✨ Features

- **Voice command activation** for:
  - Stopping applications
  - Controlling volume
  - Switching tabs
  - Scrolling content

- **Hand gesture detection**:
  - Fist to close apps
  - Finger pinch to switch tabs
  - Thumb–index distance to control volume
  - Swipe up/down gesture for scrolling

---

## 📁 Project Structure

```

project/
├── main.py             # Main Python file with gesture and voice control logic
├── README.md           # This file
├── requirements.txt    # Python dependencies
└── images/             # Add your workflow and output screenshots here

````

---

## 🔧 Requirements

Make sure you have Python 3.7 or later installed.

### Install Dependencies

```bash
pip install opencv-python mediapipe pyautogui SpeechRecognition
````

> You may also need to install `pyaudio`:
>
> On Windows:
>
> ```bash
> pip install pipwin
> pipwin install pyaudio
> ```
>
> On macOS/Linux:
>
> ```bash
> brew install portaudio
> pip install pyaudio
> ```

---

## ▶️ How to Run

Run the following command in the terminal:

```bash
python main.py
```

* Allow microphone and camera access when prompted.
* Speak one of the following commands:

  * `"stop application"` — then make a fist gesture to close the active window.
  * `"control volume"` — pinch and move fingers to increase or decrease volume.
  * `"switch tab"` — pinch gesture to switch between open tabs.
  * `"scroll"` — swipe up/down with your index finger to scroll.

Press `q` to quit the application.

---

## 🔁 Workflow

![WhatsApp Image 2025-05-29 at 09 09 43_de5ac345](https://github.com/user-attachments/assets/1963e06e-24d0-46ea-94b3-0cc91457bf59)

---

## 📸 Output Examples

![WhatsApp Image 2025-05-29 at 09 04 58_35bbf74b](https://github.com/user-attachments/assets/3e712450-1c1d-4e2b-8b86-fa19868f96d2)
![WhatsApp Image 2025-05-29 at 09 04 58_82af3a6f](https://github.com/user-attachments/assets/43540dc1-e68f-40fb-a39b-cf0c1f9544ba)


### Volume Control Gesture

![Volume Control](images/volume_control.png)

### Tab Switch Gesture

![Tab Switch](images/tab_switch.png)

---

## 🚨 Troubleshooting

* **Mic or Camera not working?**

  * Ensure permissions are granted.
  * Check device drivers or try a different device.
* **Command not recognized?**

  * Speak clearly in a quiet environment.
  * Ensure stable internet for speech recognition.



## 🙌 Acknowledgements

* [MediaPipe](https://github.com/google/mediapipe)
* [PyAutoGUI](https://github.com/asweigart/pyautogui)
* [SpeechRecognition](https://pypi.org/project/SpeechRecognition/)
* [OpenCV](https://opencv.org/)

