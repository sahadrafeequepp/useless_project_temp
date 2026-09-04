<img width="1280" height="640" alt="git (1)" src="https://github.com/user-attachments/assets/8920b256-2ba8-4988-b824-5351134eb4bd" />

# VoiceSnooze AI 🎯

> **The Voice-Silenced Anti-Alarm Clock**

---

## Basic Details
### Team Name: Nameless

### Team Members
- Team Lead: Sahad Rafeeque P P - College of Engineering Vadakara

### Project Description
A web-based alarm application that is easily stopped by small voice inputs, letting you sleep peacefully, which is the exact opposite of what an alarm clock should do.

### The Problem (that doesn't exist)
Normal alarm clocks are far too much dedicated to waking the user by giving them tasks to do which is gonna wake them up, but here that doesn't happen.

### The Solution (that nobody asked for)
We created an alarm clock that completely sabotages its own purpose by easily turning off with slight voice input.

---

## Technical Details

### Technologies Used
For Software:
- **Languages**: HTML5, CSS3 (Glassmorphism & iOS Mobile App Styling), JavaScript (ES6+)
- **Web APIs**:
  - **Web Speech API (`SpeechRecognition`)**: Continuous speech recognition for voice commands (*"stop"*, *"snooze"*, *"shut up"*, *"5 more minutes"*).
  - **Web Audio API (`AudioContext`, `AnalyserNode`, `OscillatorNode`)**: Real-time sound effect synthesizer (Siren, Buzzer, Horn, Rooster) and decibel sound analyzer.
  - **HTML5 Canvas API**: Live visualizer rendering sound spectrum & microphone frequency waves.
  - **LocalStorage API**: Persistence for multiple alarms, settings, and defeated alarm victory logs.
- **Tools**: VS Code, Python HTTP Server, Modern Web Browsers

---

## Implementation

### Installation
```bash
# Clone the repository
git clone https://github.com/sahadrafeequepp/useless_project_temp.git

# Navigate to project folder
cd useless_project_temp
```

### Run
```bash
# Start local web server using Python 3
python -m http.server 8000
```
Open your browser and navigate to:
- `http://localhost:8000/alarm.html` (VoiceSnooze Mobile App)
- `http://localhost:8000/index.html` (Useless Projects Hub)

---

## Key Features

1. ⏰ **Multiple Alarm Management**:
   - Add, edit, toggle (`ON`/`OFF`), and delete multiple custom alarms.
   - Customize labels, target times, and specific synthesizer sound effects for each alarm.

2. 🎙️ **Dual Voice & Groan Deactivation Engine**:
   - **Speech Recognition**: Silences alarm instantly when you speak any sleep phrase out loud.
   - **Decibel Sound Analyzer**: Detects soft bed grunts, sighs, yawns, and rustles exceeding your sensitivity setting.
   - **Bed Simulator Deck**: Interactive touch chips to test voice defeat mechanisms without mic access.

3. 🚨 **Fullscreen Blaring Emergency Sheet**:
   - High-energy blaring alarm overlay with sound wave animation, vibrating icons, and real-time voice shutoff listening.

4. 🏆 **Sleep Victory Log**:
   - Logs every defeated alarm with humorous sleep badges and failure stats.

---

## Project Documentation

### Screenshots
![VoiceSnooze Main App Screen](https://github.com/sahadrafeequepp/useless_project_temp/blob/main/images/Screenshot%202026-09-04%20072210.png)
*VoiceSnooze Mobile App UI featuring Hero Digital Clock, Multiple Alarms List, and Live Spectrum Visualizer*

![Blaring Alarm Overlay](https://github.com/sahadrafeequepp/useless_project_temp/blob/main/images/Screenshot%202026-09-04%20072259.png)
(https://github.com/sahadrafeequepp/useless_project_temp/blob/main/images/Screenshot%202026-09-04%20072322.png)
*Emergency Blaring Alarm overlay with real-time voice and groan listening*

![Sleep Failure History Log](https://github.com/sahadrafeequepp/useless_project_temp/blob/main/images/Screenshot%202026-09-04%20072400.png)
*Sleep Victory Log recording alarms successfully defeated by whispers and bed groans*

### Workflow Diagram
```
[ Alarm Time Triggered ] ──> [ Web Audio Synthesizer Blares Siren ]
                                          │
                                          ▼
                      [ Web Speech API & Mic Decibel Analyser Active ]
                                          │
                  ┌───────────────────────┴───────────────────────┐
                  ▼                                               ▼
     [ Spoken Voice Phrase Detected ]            [ Groan / Sigh Sound > dB Threshold ]
                  │                                               │
                  └───────────────────────┬───────────────────────┘
                                          ▼
                      [ Alarm Instantly Silenced & Cancelled ]
                                          │
                                          ▼
                      [ Defeat Recorded in Sleep Victory Log ]
```

---

## Team Contributions
- **Sahad Rafeeque P P**: Conceptualization, Web Audio & Web Speech API implementation, Mobile UI design, multi-alarm engine, and documentation.

---

Made with ❤️ at TinkerHub Useless Projects 3.0

![Static Badge](https://img.shields.io/badge/TinkerHub-24?color=%23000000&link=https%3A%2F%2Fwww.tinkerhub.org%2F)
![Static Badge](https://img.shields.io/badge/UselessProjects--26-26?link=https%3A%2F%2Ftinkerhub.org%2Fevents%2F1M8ORET9A1%2Fuseless-projects-3.0)
