
GestureSynth 🖐🎵

GestureSynth is an interactive web-based digital instrument that allows you to play music and control a synthesizer completely through hand movements in front of your camera.
Powered by MediaPipe Hands for real-time computer vision tracking and Tone.js for high-quality audio synthesis, the entire engine runs locally inside your browser with zero server latency.

✨ Features

• Real-Time Computer Vision: Leverages your webcam to instantly track precise finger counts and wrist rotations.
• Dynamic Chord Selection (Left Hand): Selects fundamental musical chords and dynamically swaps their quality between Major and Minor variations.
• Audio & Effect Expression (Right Hand): Intuitively maps physical depth and height to master volume, octaves, and audio filters.
• Serverless & Privacy-Focused: No data leaves your machine; all video frame processing and audio generation happen locally in the browser.

🎮 How to Play

Grant the application camera and audio permissions, position yourself so your hands are visible, and use the following gestures:

✋ Left Hand — Chords & Quality

• 1 to 5 Fingers Up → Triggers chords C · D · E · F · G
• Make a Fist (0 Fingers) → Mutes the instrument (Silent)
• Tilt Hand Inward → Switches chord flavor to Major
• Tilt Hand Outward → Switches chord flavor to Minor

🤚 Right Hand — Volume, Octaves & Effects

• Move Up / Down → Adjusts the Volume
• Move Forward / Backward → Modulates Audio Effects (Distortion & Filter)
• Finger Count → Shifts the current Octave register:
	• 1–2 fingers → Octave 3
	• 3–4 fingers → Octave 4
	• 5 fingers → Octave 5

🛠️ Tech Stack

• MediaPipe Hands — Real-time ML hand and finger tracking pipeline.
• Tone.js — Web Audio framework for creating interactive music in the browser.
• Frontend Basics — HTML5, CSS3, and modern JavaScript (ES6+).

🚀 Getting Started

1. Clone the repository:bash

2. Navigate into the project directory:bash
cd GestureSynth
Use code with caution.

3. Run the app:
Simply open index.html directly in any modern web browser, or use a local development extension like Live Server in VS Code.
