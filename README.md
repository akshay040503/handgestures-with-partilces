# AI Interactive Particle Playground

An interactive web-based 3D particle simulation that responds to **hand gestures and facial expressions** using computer vision and AI.

The project combines **Three.js**, **MediaPipe Hands**, and **Face API** to create a real-time particle playground controlled through webcam interaction.

---

## Features

- Real-time **hand tracking using MediaPipe**
- **Gesture-controlled particle system**
- Multiple particle templates:
  - Heart
  - Flower
  - Saturn
  - Firework
  - Circle
- **Pinch gesture interaction**
  - Attract particles
  - Repel particles
  - Create particle bursts
- **Emotion detection using Face API**
- Dynamic color changes
- Adjustable particle count
- Particle trail effects
- 3D camera controls

---

## Technologies Used

- **Three.js** – 3D rendering
- **MediaPipe Hands** – Hand tracking
- **Face API.js** – Emotion detection
- **JavaScript (ES6)**
- **HTML5 + CSS3**
- **WebGL**

---

## Project Structure
project-folder
│
├── index2.html
├── index3.html
├── main.js
├── styles.css
└── README.md


Run the Project in the Browser (Quick Start)
1. Download or Clone the Repository

Download the ZIP from GitHub or clone it:

git clone https://github.com/your-username/particle-playground.git
2. Open the Project Folder

Navigate to the project directory on your computer.

Example:

particle-playground/
│
├── index2.html
├── index3.html
├── main.js
├── styles.css
3. Open the Project in a Browser

Simply double-click the HTML file.

For example:

index3.html

or

index4.html

This will open the project directly in:

Chrome
Edge
Firefox
4. Allow Camera Access

When the page loads, the browser will ask for camera permission.

Click:

Allow

The webcam is required for:

Hand tracking (MediaPipe)
Emotion detection (Face API)
5. Interact With the System

Once the page loads:

Show your hand to the camera
Move your hand to attract particles
Pinch (thumb + index) to repel particles
Different number of fingers changes particle shapes
Facial expressions affect the particle behavior
Important Notes

If the camera does not work:

Use Google Chrome
Enable camera permissions
Refresh the page
