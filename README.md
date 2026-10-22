# 🪞 Fog Mirror

An interactive in-browser bathroom mirror experiment. The glass naturally clouds with realistic condensation, steam. Breathe or blow towards your microphone to fog up the surface, and use your finger or mouse to draw, write messages, or wipe it clear.

Everything runs entirely on the client side using pure JavaScript, Canvas API, Web Audio API, and MediaPipe face tracking. No video or audio data ever leaves your device.

---

## ✨ Features

- **Interactive Condensation:** Blow directly into your microphone to cast warm fog and steam onto the mirror in real-time.
- **Glass Drawing Physics:** Smooth fingertip drawing with Bézier curve interpolation and squeak audio effects.
- **Wide Wipe Gesture:** Hold `Shift` (or right-click drag) to wipe away large areas with your palm.
- **Face Landmark Tracking:** Leverages MediaPipe Face Detection to place breath plumes accurately relative to your mouth.
- **One-Tap Photo Capture:** Take a crisp snapshot of your foggy artwork directly to your device without UI elements.
- **100% Private & Local:** All processing is done strictly in the browser. Zero server uploads.

---

## 🎮 Controls & Shortcuts

| Action | Control |
| :--- | :--- |
| **Draw / Write** | Click / Touch & Drag |
| **Wide Fist Wipe** | Hold `Shift` (or Right-Click) + Drag |
| **Fog the Glass (Breathe)** | Blow into Microphone or Hold `Spacebar` |
| **Take Photo / Save** | Click **Camera Button** or press `S` (or `C`) |
| **Reset Fog** | Press `C` |
| **Toggle Sound** | Press `M` |
| **Exit Mirror** | Press `Esc` |

---

## 🚀 Quick Start / Local Setup

Because the project accesses the camera and microphone, browsers require a secure origin (`http://localhost` or `https://`). Opening the file directly via `file://` will block camera access.

### 1. Clone the repository
```bash
git clone https://github.com/your-username/fog-mirror.git
cd fog-mirror
