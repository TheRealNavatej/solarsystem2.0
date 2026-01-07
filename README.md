# 🌌 Ultra-Realistic Gesture-Controlled Solar System

### **A Human–Computer Interaction (HCI) exploration of touchless spatial navigation**

---

## 🧠 Research Framing (Read This First)

> **This project is not a graphics demo.**
> It is an **experimental HCI system** that investigates how **human hand gestures can function as a primary interface** for navigating complex, high-dimensional spatial information.

The Solar System is used **as the interaction medium**, not the goal.

---

## 🔍 What Problem Does This Address?

Traditional interfaces for 3D exploration rely on:

* Mouse & keyboard mappings
* Touchscreens
* Controllers

These methods:

* Break spatial intuition
* Require learned mappings
* Do not scale well to immersive or public environments

### ❗ Core Question

**Can natural human gestures replace conventional input devices for complex 3D navigation without training?**

This project is a **functional prototype answering that question**.

---

## ✋ Interaction Model (HCI Core)

This system introduces a **gesture-to-semantic-intent mapping**, not gesture-to-button mapping.

### 🧠 Gesture Semantics

| Human Intent | Gesture      | System Interpretation     |
| ------------ | ------------ | ------------------------- |
| Focus        | Closed fists | Single object (Sun)       |
| Explore      | Open hands   | Global system overview    |
| Select       | Finger count | Discrete object selection |

> The user never “learns controls” —
> **the system interprets intent**.

This is a key **HCI design principle**.

---

## 🎥 Why the Solar System?

The Solar System provides:

* Multiple objects
* Hierarchical scale
* Continuous motion
* Natural spatial relationships

This makes it an **ideal testbed** for evaluating:

* Spatial navigation
* Focus switching
* Cognitive load
* Gesture ambiguity

The visuals support the interaction — they are not the research novelty.

---

## 🧩 System Architecture (Conceptual)

**Human → Perception → Intent → Spatial Response**

1. **Human Gesture Input**

   * Dual-hand tracking
   * 21 landmarks per hand

2. **Perceptual Interpretation**

   * Finger count
   * Hand symmetry
   * Gesture state classification

3. **Intent Mapping**

   * Overview
   * Focus
   * Selection

4. **System Response**

   * Camera trajectory
   * Object framing
   * Information surfacing

This pipeline is **HCI-first**, graphics-second.

---

## 🧠 Key HCI Contributions

### ✅ Touchless Interaction

* No physical input devices
* Suitable for public & sterile environments

### ✅ Low Cognitive Load

* No gesture memorization
* Natural mappings (open = explore, closed = focus)

### ✅ Continuous Feedback

* Visual HUD
* Smooth camera interpolation
* No abrupt state changes

### ✅ Accessibility-Aware Design

* Can be extended for mobility-limited users
* Reduces dependence on fine motor control

---

## 🛠 Technical Stack (Supporting Role)

> Technology enables the interaction — it is not the contribution.

* **Three.js** — Real-time spatial rendering
* **MediaPipe Hands** — Human perception layer
* **WebGL** — GPU acceleration
* **HTML Canvas** — Procedural world generation
* **Vanilla JavaScript** — Deterministic control logic

No backend. No frameworks. Minimal abstraction.

---

## 🚀 Running the Prototype

```bash
1. Clone or download the repository
2. Open index.html in a modern browser
3. Allow webcam access
4. Use your hands to explore
```

**Recommended:**
✔ Good lighting
✔ Hands visible to camera

---

## 🧪 Evaluation Context (Important)

This prototype can be evaluated on:

* Learnability (no instructions needed)
* Gesture recognition accuracy
* Navigation efficiency
* User fatigue
* Error tolerance

It is suitable for:

* HCI coursework
* Research demos
* Lab studies
* Public installations

---

## 🔮 Research Extensions

* Gesture ambiguity resolution
* Multi-user interaction
* Eye-tracking integration
* VR / WebXR embodiment
* Adaptive gesture learning


