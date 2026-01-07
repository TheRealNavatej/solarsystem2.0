🌌 Ultra-Realistic Gesture-Controlled Solar System

An interactive, cinematic 3D Solar System simulation controlled entirely using hand gestures, built with Three.js and MediaPipe Hands.
This project blends computer graphics, computer vision, and real-time interaction to create a touch-free astronomical exploration experience.

🚀 Project Overview

This application renders an ultra-realistic solar system with dynamic orbits, procedural planet textures, moons, rings, starfields, and cinematic camera transitions — all navigated without a mouse or keyboard.

Instead of traditional UI controls, hand gestures act as the navigation language, allowing users to:

Zoom into individual planets

Switch to full solar system overview

Focus directly on the Sun

View real-time planetary information via a HUD

This is not just visualization — it’s human-computer interaction through spatial gestures.

✋ Gesture-Based Navigation Logic
Gesture	Action
1–9 Fingers (any hand)	Navigate to planets (Mercury → Pluto)
Both hands open (10 fingers)	Solar System overview
Both fists closed (0 fingers)	Focus on the Sun

Gesture recognition is performed in real time using webcam input and MediaPipe’s hand landmark detection.

🧠 Key Technical Concepts Used
1. Procedural Planet Texturing

Each planet texture is generated dynamically using HTML Canvas

Simulates:

Craters (Mercury)

Thick atmospheres (Venus)

Continents, oceans, clouds (Earth)

Dust storms (Mars)

Gas bands and storms (Jupiter & Saturn)

Ice and methane layers (Uranus, Neptune, Pluto)

2. Real-Time Hand Tracking

Uses 21 hand landmarks per hand

Finger count calculated via landmark geometry

Supports dual-hand detection

Robust against partial occlusion

3. Cinematic Camera System

Smooth camera interpolation (LERP)

Dynamic camera offsets based on planet size

Automatic focus transitions

Filmic tone mapping (ACES)

4. Astronomical Simulation

Orbital motion using pivot groups

Independent planet rotation & moon orbits

Scaled relative distances and sizes (visual accuracy focused)

🖥️ Tech Stack

Three.js – 3D rendering engine

MediaPipe Hands – Real-time hand tracking

WebGL – GPU-accelerated graphics

HTML Canvas – Procedural texture generation

JavaScript (ES6) – Core logic

No backend. Runs entirely in the browser.

📊 Features

🌍 9 Celestial bodies (Sun + 8 planets + Pluto)

🌑 Planetary moons with independent orbits

💫 Saturn ring system with shadowing

🌌 Deep-space starfield

🧭 HUD with planet metadata

🎥 Cinematic transitions

🖐️ Touch-free interaction

📦 How to Run

Clone or download the repository

Open the index.html file in a modern browser

Allow webcam access

Use hand gestures to navigate

⚠️ Best experienced in a well-lit environment with hands clearly visible.

🧪 Tested On

Chrome (Recommended)

Edge

Firefox (limited MediaPipe performance)

🎯 Why This Project Is Different

Most solar system projects are:

Click-based

Static

Educational visuals only

This project explores a new interaction paradigm:

“What if astronomical exploration didn’t require physical interfaces at all?”

It demonstrates how gesture-driven interfaces can be used in:

Education

Museums & planetariums

AR/VR preprocessing

Touchless public installations

🔮 Future Enhancements

Voice-assisted navigation

VR / WebXR support

Real astronomical scaling toggle

Asteroid belt & Kuiper belt simulation

Educational narration mode

📜 License

This project is open for educational and research purposes.
Attribution appreciated if reused or extended.
