# 🧊 Voxel AR Hologram Builder 

A browser-based Augmented Reality (AR) voxel architect tool inspired by creative coding concepts. This project allows users to build glowing, 3D wireframe structures in mid-air using hand gestures, entirely within the web browser.

![Version](https://img.shields.io/badge/Version-1.0-cyan)
![Tech](https://img.shields.io/badge/Tech-HTML5%20|%20Three.js%20|%20MediaPipe-blue)

## ✨ Features

* **✋ 2-Hand Tracking:** Utilizes Google's modern AI (MediaPipe Tasks Vision) to track both hands simultaneously in real-time.
* **🏗️ Raycasting & Snap-to-Grid:** Employs Three.js raycasting to detect existing blocks, allowing users to stack voxels precisely with a "Ghost/Hover Voxel" preview.
* **🔄 3D World Rotation:** Grab and rotate the entire 3D stage using your off-hand to view your creation from any angle.
* **🌟 Glowing Neon Aesthetics:** Features a Tron-inspired cyan wireframe design with CSS-driven bloom/glow effects for a futuristic HUD feel.
* **⚡ Zero Setup:** Runs entirely on the client-side browser via CDN. No local installations or Node.js required.

## 🎮 How to Use (Controls)

Once the camera is initialized and the AI model is loaded:

1.  **Right Hand (Draw/Build):** * Move your index finger to aim. A dashed "ghost" block will follow your finger and snap to the nearest grid space or existing block.
    * **Pinch** (bring your thumb and index finger together) to place a solid glowing voxel.
2.  **Left Hand (Rotate):**
    * **Pinch and drag** in mid-air to rotate the entire 3D environment along the X and Y axes.
3.  **UI Buttons:**
    * `[ Open Cam ]`: Initializes the webcam and AI tracking.
    * `[ Reset Block ]`: Clears all drawn voxels while preserving the core tracking system.

## 🚀 Running the Project

### Option 1: Live Demo (GitHub Pages)
*(Note: Replace this line with your actual GitHub Pages link once deployed)*
[Play the Live Demo Here](https://your-username.github.io/your-repo-name/](https://jefanno1.github.io/Voxel-Gesture-BlockBuilder/)

### Option 2: Run Locally
1. Clone this repository:
   ```bash
   git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
