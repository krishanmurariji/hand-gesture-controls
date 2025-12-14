# Kinetic Hand: Interactive 3D Particle System

A real-time, interactive WebGL particle system driven by computer vision. This project uses **Three.js** for high-performance rendering and **Google MediaPipe** for hand tracking, allowing users to control particle formations, physics, and interactions using simple hand gestures.

## 🚀 Features

*   **Real-time Hand Tracking:** Uses GPU-accelerated vision to track hand landmarks directly in the browser.
*   **Mathematical Morphing:** Particles fluidly interpolate between parametric shapes (Heart, Saturn, DNA Helix, Fibonacci Sphere) without destroying/recreating meshes.
*   **Physics Interactions:**
    *   **Blast:** Simulates an explosion force pushing particles outward.
    *   **Drag:** Physically grab and move the particle cluster in 3D space.
*   **Mobile Responsive:** Optimized particle count and UI for mobile devices.

## 🛠 Tech Stack

*   **Rendering:** [Three.js](https://threejs.org/) (WebGL)
*   **Computer Vision:** [MediaPipe Hands](https://developers.google.com/mediapipe/solutions/vision/hand_landmarker)
*   **Language:** Vanilla JavaScript (ES6 Modules)

## 🎮 Controls & Gestures

The system tracks one hand using the webcam.

| Gesture | Action / Shape | Description |
| :--- | :--- | :--- |
| **Fist (0 Fingers)** | ⚪ **Sphere** | Resets particles to a random spherical distribution. |
| **1 Finger** | ❤️ **Heart** | Morphs particles into a 3D parametric heart. |
| **2 Fingers** | 🪐 **Saturn** | Forms a planet with a distinct ring system. |
| **3 Fingers** | 🧬 **Helix** | Forms a double-helix DNA strand. |
| **4 Fingers** | 🌀 **Spiral Sphere** | Arranges particles in a Fibonacci spiral sphere. |
| **Open Hand (5)** | 💥 **BLAST** | Triggers a high-speed explosion effect. |
| **Pinch (👌)** | ✋ **DRAG** | "Grab" the shape to move it around the screen. |

## 📦 How to Run

1. Clone the repository.
2. Serve the `index.html` file using a local server (required for webcam permissions and ES modules).

<!-- Add this at the very bottom of your README.md -->

---

<div align="center">

## 👨‍💻 About the Developer

### **Krishan Murari**
**Web Developer | Android Enthusiast | Poet**

<img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="28"> **Hey there!**
I am a Full Stack Developer with a passion for building beautiful applications and exploring new technologies. When I'm not coding or debugging, you can find me writing poetry or watching movies.

Currently, I am focused on **JavaScript & React** development while mastering **Data Structures and Algorithms**.

<br/>

### 🌐 Connect with Me

<a href="https://krishanmurari.live/" target="_blank">
<img src="https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Portfolio" />
</a>
<a href="https://linkedin.com/in/krishan-murari/" target="_blank">
<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
<a href="https://twitter.com/KrishanMuraari" target="_blank">
<img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter" />
</a>
<a href="https://www.instagram.com/krishanmurariji/" target="_blank">
<img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" />
</a>
<a href="https://github.com/krishanmurariji" target="_blank">
<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
</a>

<br/>

### 🛠️ Tech Toolbox

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-0095D5?style=flat-square&logo=kotlin&logoColor=white)
![Android Studio](https://img.shields.io/badge/Android_Studio-3DDC84?style=flat-square&logo=android-studio&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=flat-square&logo=javascript&logoColor=F7DF1E)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

<br/>

_"Coding is my interest, poetry is my soul."_

</div>
