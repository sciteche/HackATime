# 🎵 Melody Flow - Immersive Text Editor

**Melody Flow** is an ultimate audiovisual writing experience designed to turn your typing sessions into a symphony. This single-file web application combines a robust text editor with a real-time synthesizer, dynamic particle physics, and atmospheric weather effects to help you get into the "flow" state.

## ✨ Key Features

### 🎹 Advanced Audio Engine

Typing generates music in real-time using the **Web Audio API**.

* **9 Instrument Modes:**
  * 🎵 **Xylophone** (Sine)
  * 🎹 **Piano** (Square with envelope)
  * 🎸 **Guitar** (Sawtooth pluck)
  * 🥁 **Drums** (Real-time synthesized Kick & Snare beats)
  * 🪈 **Flute** (Breathy triangle wave)
  * ⛪ **Organ** (Sustained sawtooth)
  * 🔔 **Bell** (Metallic sine ring)
  * 👾 **8-Bit** (Retro game blips)
  * 🎻 **Violin** (Slow-attack sawtooth)

* **Spatial Effects:** Toggleable **Reverb** to add depth and atmosphere to your typing.
* **Scale Mapping:** Keys are mapped to a C4-C5 scale to ensure harmonious output.

### 🎨 Visual Immersion

* **Dynamic Themes:** Switch instantly between:
  * 🌅 **Sunset:** Warm, productive gradients.
  * 🌃 **Cyberpunk:** Neon accents on a dark background.
  * 🎍 **Zen:** Clean, minimalist whitespace.

* **Particle Physics:** Sparks and particles explode from the caret as you type.
* **Audio Visualizer:** A live frequency bar graph dances at the bottom of the screen.
* **Weather System:** Choose your atmosphere with falling **Snow ❄️, Rain 🌧️, Hearts ❤️, or Stars ⭐**. Watch them pile up at the bottom of the screen!

### ⚡ Productivity & Gamification

* **Combo System:** Type faster to build your Combo counter. Reach **20x Combo** to trigger the "Screen Shake" intensity mode.
* **Live Analytics:** Real-time **Words Per Minute (WPM)** and **Character Count** tracking.
* **Recording Studio:** Record your typing performance and download it as a high-quality `.wav` file.

## 🚀 Quick Start

This is a standalone application. No servers, node_modules, or installation required.

1. Download the `melody_editor_v2.html` file.
2. Open it in any modern web browser (Chrome, Edge, Firefox, Safari).
3. **Click the "Start" Overlay:** You must click the initial overlay to unlock the Audio Engine (browser security requirement).
4. Start typing!

## 🎮 Controls

| Control | Action | Description |
| :--- | :--- | :--- |
| **Theme Selector** | Dropdown | Switch between Sunset, Cyberpunk, and Zen visual styles. |
| **Font Selector** | Dropdown | Change editor typography (Sans, Monospace, Serif, Comic, etc.). |
| **Weather** | Dropdown & Buttons | Select particle type, toggle on/off, or clear the accumulated pile. |
| **Instrument** | Dropdown | Change the sound synthesized for every keystroke. |
| **Reverb** | Button | Toggle echo/spatial audio effects. |
| **Record** | Button | Start capturing audio. (Stop to enable download). |
| **Save** | Button | Download the recorded session as a `.wav` file. |

## 🛠️ Technical Details

* **Architecture:** Zero-dependency, single-file HTML5.
* **Audio:** Built entirely with the Web Audio API (`OscillatorNode`, `GainNode`, `ConvolverNode`, `AnalyserNode`). No external audio samples are used; everything is synthesized code.
* **Visuals:** Canvas API for particles/visualizer and CSS3 for UI glassmorphism.
* **Privacy:** All data remains local in your browser. Nothing is sent to a server.

## ⚠️ Troubleshooting

* **No Sound?** Ensure you clicked the "Click to Start" overlay. Browsers block audio that starts without user interaction. Check your system volume and ensure the tab isn't muted.
* **Recording:** Recording relies on the `MediaStreamDestination` API. It works best in Chrome and Firefox.

## 📄 License

Open Source. Feel free to modify, remix, and compose!

## 📬 Contact

For questions, support, or feedback, please reach out to us at: contact@sciteche.com

## Changing moUSE Cursor

Changing mose cursor to guitar in this window will add a more cool and amazing effect!! to shock all users HaHa!! That sounds really amazing!! cool Huh! Wohooo it's about to complete!