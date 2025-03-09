# Monkey Menace Prevention System

## Overview
The **Monkey Menace Prevention System** is a real-time monitoring solution designed to protect properties from monkey intrusions. Using advanced machine learning with **TensorFlow.js** and **Teachable Machine**, this web-based application processes live video feeds to identify monkey presence and triggers immediate customizable audio alerts. 

Developed specifically for areas prone to monkey disturbances, this system helps prevent property damage, food theft, and potential human-wildlife conflicts. The application features a sleek, responsive UI built with **TailwindCSS** and is optimized for deployment on **Raspberry Pi** devices, allowing for affordable monitoring stations to be placed at strategic locations.

## Features
* **Real-time Menace Detection**: Uses TensorFlow.js models for instant monkey identification via webcam feed.
* **Proactive Alert System**: Customizable sound notifications with adjustable frequency, volume, and detection thresholds.
* **Dynamic UI**: Responsive design with live updates using TailwindCSS animations.
* **Panel Toggles**: Show or hide video feed and detection control panels.
* **Raspberry Pi Optimization**: Lightweight and efficient for low-power devices.

## Tech Stack
* **Frontend**: HTML, CSS (TailwindCSS), JavaScript
* **Machine Learning**: TensorFlow.js, Google Teachable Machine
* **Hardware**: Raspberry Pi (for deployment)

## Project SetUp
1. Clone the Repository
   ```bash
   git clone https://github.com/Kinsuksingh/MonkeyDetection.git
   cd MonkeyDetection
   ```



2. Access the Web App
   Open your browser and visit:
   ```
   http://localhost:8000
   ```

## Live Demo
Try the system yourself: [https://kinsuksingh.github.io/MonkeyDetection/](https://kinsuksingh.github.io/MonkeyDetection/)

**Note:** For the live demo, you can use sample images of monkeys or test with your webcam. Permission will be requested to access your camera. For privacy reasons, no video data is stored on our servers.

## Usage
1. **Enable Webcam**: Ensure your webcam permissions are granted.
2. **Start Detection**: The live video feed will begin, and the detection model will analyze frames in real-time.
3. **Customize Alerts**: Use the controls on the right panel to adjust sound frequency, volume, and detection sensitivity.
4. **Toggle Panels**: Show or hide the video feed and control panels using the provided toggle switches.

## Project Structure
```
.
├── index.html   # Main HTML file
├── style.css    # TailwindCSS for styling
├── script.js    # Main JS file for detection logic
├── model/       # TensorFlow.js models
├── assets/      # Images and sound files
└── README.md    # Project documentation
```

## Team
* **Kinsuk Singh**
* **Sourabh Bindal**
* **Imtiyazuddin**
* **Vijay Kumar**

## Future Enhancements
* 📈 **Model Optimization**: Further enhance model accuracy and reduce latency.
* 📲 **Mobile Compatibility**: Improve performance on mobile devices.
* 🔔 **Notification System**: Add email or app push notifications.
* 🔄 **Multiple Animal Detection**: Expand to detect various animal species.
* 📊 **Statistics Dashboard**: Add analytics for detection events over time.


## Acknowledgements
* TensorFlow.js team for the machine learning framework
* Google's Teachable Machine for simplified model training
* The TailwindCSS team for the utility-first CSS framework
