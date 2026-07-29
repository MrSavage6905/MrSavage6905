<div align="center">

<svg width="100%" height="auto" viewBox="0 0 900 220" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bg" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#0a0e14"/>
      <stop offset="100%" stop-color="#0d1520"/>
    </linearGradient>
    <linearGradient id="glow" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#00F0FF" stop-opacity="0"/>
      <stop offset="50%" stop-color="#00F0FF" stop-opacity="1"/>
      <stop offset="100%" stop-color="#00F0FF" stop-opacity="0"/>
    </linearGradient>
    <filter id="softGlow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="3" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <filter id="textGlow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="4" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <!-- background -->
  <rect width="900" height="220" fill="url(#bg)"/>

  <!-- faint grid -->
  <g stroke="#132030" stroke-width="1">
    <line x1="0" y1="40" x2="900" y2="40"/>
    <line x1="0" y1="80" x2="900" y2="80"/>
    <line x1="0" y1="140" x2="900" y2="140"/>
    <line x1="0" y1="180" x2="900" y2="180"/>
    <line x1="60" y1="0" x2="60" y2="220"/>
    <line x1="200" y1="0" x2="200" y2="220"/>
    <line x1="700" y1="0" x2="700" y2="220"/>
    <line x1="840" y1="0" x2="840" y2="220"/>
  </g>

  <!-- circuit traces left -->
  <g fill="none" stroke="#1e3a4a" stroke-width="2">
    <path d="M0,40 H60 L80,60 V110 L60,130 H0"/>
    <path d="M0,180 H100 L120,160 H200"/>
    <path d="M30,0 V20 L50,40"/>
    <circle cx="60" cy="40" r="4" fill="#0d1520" stroke="#2a5a70"/>
    <circle cx="80" cy="110" r="4" fill="#0d1520" stroke="#2a5a70"/>
    <circle cx="120" cy="160" r="4" fill="#0d1520" stroke="#2a5a70"/>
  </g>

  <!-- circuit traces right -->
  <g fill="none" stroke="#1e3a4a" stroke-width="2">
    <path d="M900,40 H840 L820,60 V110 L840,130 H900"/>
    <path d="M900,180 H800 L780,160 H700"/>
    <path d="M870,0 V20 L850,40"/>
    <circle cx="840" cy="40" r="4" fill="#0d1520" stroke="#2a5a70"/>
    <circle cx="820" cy="110" r="4" fill="#0d1520" stroke="#2a5a70"/>
    <circle cx="780" cy="160" r="4" fill="#0d1520" stroke="#2a5a70"/>
  </g>

  <!-- animated pulse traveling along left trace -->
  <circle r="4" fill="#00F0FF" filter="url(#softGlow)">
    <animateMotion dur="4s" repeatCount="indefinite"
      path="M0,40 H60 L80,60 V110 L60,130 H0 Z"/>
  </circle>
  <circle r="4" fill="#00F0FF" filter="url(#softGlow)">
    <animateMotion dur="3.2s" repeatCount="indefinite" begin="0.6s"
      path="M900,40 H840 L820,60 V110 L840,130 H900 Z"/>
  </circle>
  <circle r="3" fill="#00F0FF" filter="url(#softGlow)" opacity="0.8">
    <animateMotion dur="2.4s" repeatCount="indefinite" begin="1s"
      path="M0,180 H100 L120,160 H200"/>
  </circle>
  <circle r="3" fill="#00F0FF" filter="url(#softGlow)" opacity="0.8">
    <animateMotion dur="2.4s" repeatCount="indefinite" begin="1.4s"
      path="M900,180 H800 L780,160 H700"/>
  </circle>

  <!-- scanning glow line -->
  <rect x="0" y="0" width="900" height="2" fill="url(#glow)" opacity="0.6">
    <animate attributeName="y" values="0;218;0" dur="6s" repeatCount="indefinite"/>
  </rect>

  <!-- main text -->
  <text x="450" y="105" text-anchor="middle" font-family="Fira Code, monospace"
        font-size="46" font-weight="700" fill="#00F0FF" filter="url(#textGlow)">
    Srivathsan
    <animate attributeName="opacity" values="0.7;1;0.7" dur="3s" repeatCount="indefinite"/>
  </text>

  <!-- subtitle -->
  <text x="450" y="140" text-anchor="middle" font-family="Fira Code, monospace"
        font-size="17" fill="#7fdfe8" opacity="0.9">
    &lt;/&gt; Embedded Systems &amp; Edge AI Engineer
  </text>

  <!-- blinking cursor -->
  <rect x="638" y="126" width="10" height="18" fill="#00F0FF">
    <animate attributeName="opacity" values="1;0;1" dur="1s" repeatCount="indefinite"/>
  </rect>
</svg>

</div>

---

### 🚀 About Me

- 🎓 **Education:** Final Year Electronics and Communication Engineering (ECE) Student
- 💡 **Core Focus:** Embedded Systems Design, Edge AI, and IoT Sensor Integration
- 🧠 **Mission:** Bridging hardware and software by deploying machine learning algorithms on resource-constrained microcontrollers and single-board computers.
- 🔌 **Technical Interests:** Sensor Data Acquisition, Real-time Feedback Loops, Computer Vision at the Edge, and Hardware-Software Co-Design.
- 🌱 **Currently Learning:** TinyML, Edge AI Optimization, Embedded ML Frameworks, and Advanced Microcontroller Architectures.

---

### 🛠️ Hardware & Technical Domain Knowledge

#### **Programming & Core Languages**
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

#### **Development Boards & Hardware**
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-C51A4A?style=for-the-badge&logo=raspberry-pi&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)

#### **Hardware & Sensor Interfacing**
- **Sensors:** MPU6050 (6-axis IMU / Accelerometer & Gyroscope), Current Sensors, Motion Sensors
- **Peripherals & Displays:** OLED Displays, Buzzers, Push Buttons, RTC (Real-Time Clock) Modules
- **Communication Protocols:** Serial Communication, I2C, SPI, UART

#### **AI / ML & Computer Vision**
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
- **Vision Tools:** MediaPipe (Hand Tracking), YOLO (Object Detection), EfficientNet

#### **Development Tools & Simulation**
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Arduino IDE](https://img.shields.io/badge/Arduino_IDE-00979D?style=for-the-badge&logo=arduino&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
- **Hardware Simulation:** Wokwi Simulator

---

### 📌 Deep Dive: Projects & Implementations

#### 🎵 **Smart Musical Instrument Tuner & Practice System**
- **Hardware:** ESP32, OLED Display, Buzzer, Push Buttons
- **Key Features:** Built an interactive menu navigation system using tactile push buttons, real-time visual tuning feedback via OLED display, and audio alert notifications with buzzer routines.

#### ⚡ **Intelligent Non-Intrusive Load Monitoring (NILM)**
- **Hardware/Tech:** Raspberry Pi, Current Sensors, Machine Learning
- **Key Features:** Continuous energy monitoring and data acquisition using non-intrusive current sensing, paired with AI models for individual appliance identification and consumption analysis.

#### ❤️ **Edge AI Healthcare & Wellness Monitoring**
- **Hardware/Tech:** ESP32, MPU6050 IMU, RTC Module, OLED Display
- **Key Features:** Motion tracking and posture classification using MPU6050 accelerometer/gyroscope data, timed hydration reminders via RTC, and on-device health stats rendering.

#### 🤟 **Indian Sign Language (ISL) Recognition**
- **Tech Stack:** Python, OpenCV, MediaPipe
- **Key Features:** Real-time multi-keypoint hand tracking and gesture recognition for translating sign language inputs into automated text/predictions.

#### 🌊 **Underwater Pollution Detection Framework**
- **Tech Stack:** Python, YOLO, EfficientNet, OpenCV
- **Key Features:** Computer vision model trained to detect and classify aquatic debris and environmental pollutants using object detection and image classification architectures.

---
