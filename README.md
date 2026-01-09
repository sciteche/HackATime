# 🎵 Xylophone Text Editor

An immersive, audiovisual text editing experience that turns your typing into music. This lightweight web application combines a functional text editor with a generative synthesizer and interactive weather effects.

![Project Status](https://img.shields.io/badge/status-active-success.svg)
![License](https://img.shields.io/badge/license-MIT-blue.svg)

## ✨ Features

### 🎹 Generative Audio
Every keystroke generates a unique sound using the **Web Audio API**.
* **4 Instrument Modes:**
    * 🎵 **Xylophone** (Sine Wave)
    * 🎹 **Piano** (Square Wave)
    * 🎸 **Guitar** (Sawtooth Wave)
    * 🥁 **Drums** (Triangle Wave)
* **Scale:** Plays random notes from the C4 Major scale (C4-C5) to ensure pleasant harmony regardless of typing speed.

### ❄️ Dynamic Weather System
Visual particles fall and accumulate at the bottom of the screen based on your activity.
* **Modes:** Snow ❄️, Rain 🌧️, Hearts ❤️, Stars ⭐.
* **Interactive:** Typing faster creates "bursts" of weather particles.
* **Accumulation:** Watch the elements pile up at the bottom of the editor over time.

### 🎙️ Recording Studio
* **Record:** Capture your typing sessions as audio tracks.
* **Playback:** Listen to your composition immediately.
* **Export:** Download your masterpiece as a `.wav` file.

## 🚀 Installation & Usage

This is a standalone, client-side application. No server, Node.js, or build process is required.

1.  **Download:** Clone this repository or download the source code.
2.  **File Setup:** Ensure you have the `index.html` file containing the code.
3.  **Run:** Double-click `index.html` to open it in your default web browser.

> **Note:** Because this app uses the Web Audio API, you must interact with the page (click anywhere) at least once to unmute the audio engine.

## 🎮 Controls

| Control Area | Action | Description |
| :--- | :--- | :--- |
| **Instruments** | Click Icons | Switch between Xylophone, Piano, Guitar, or Drums. |
| **Weather** | Click Icons | Change the falling particles (Snow, Rain, etc.). |
| **Editor** | Type Keys | Generates sound and text. |
| **Font** | Dropdown | Switch fonts (Arial, Courier, Times, etc.). |
| **Record** | Button | Start/Stop audio recording. |
| **Play** | Button | Play back the last recorded session. |
| **Download** | Button | Save the recording to your computer. |
| **Clear Snow** | Button | Resets the particle pile-up at the bottom. |
| **Disable Weather** | Button | Toggles visual effects on/off for performance. |

## 🛠️ Built With

* **HTML5** - Structure and layout.
* **CSS3** - Animations, gradients, flexbox, and keyframes.
* **JavaScript (Vanilla)** - Logic, DOM manipulation.
* **Web Audio API** - Real-time sound synthesis (Oscillators/GainNodes).
* **MediaStream Recording API** - Audio capture and export.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1.  Fork the project
2.  Create your feature branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

Thanks!!!!