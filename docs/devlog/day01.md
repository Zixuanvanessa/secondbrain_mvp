# Day 01 – Core Interaction Prototype

**Goal:**  
Validate the core interaction loop for a reflective, voice-based interface.

---

## What I Built

### 1. Instant Camera-First Interface
- Implemented a web-based interface that opens directly into the **front-facing camera preview**
- No login, no menu — the user is immediately “present” in the interface

**Rationale:**  
This removes friction and reinforces the idea of self-reflection as a first-person experience.

---

### 2. Tap-to-Record Voice Interaction
- Implemented tap-anywhere behavior to **start / stop speech recognition**
- Clear visual feedback when recording is active (“录音中”)

**Rationale:**  
I wanted the interaction to feel lightweight and embodied — closer to a gesture than a button press.

---

### 3. Live Speech-to-Text Overlay
- Recognized speech is displayed **in real time**
- White text over a dark semi-transparent background bar at the lower half of the screen

**Rationale:**  
This allows users to immediately *see* their thoughts as they speak, without breaking visual focus.

---

## Technical Notes
- Built using vanilla HTML/CSS/JS in VS Code
- Browser-based speech recognition (Web Speech API)
- Camera access via `getUserMedia`

---

## Outcome
By the end of Day 01, I had a working prototype that:
- Opens directly into a reflective mode
- Accepts spoken input with minimal friction
- Visually mirrors thought back to the user in real time

This validated the core interaction pattern for the MVP.
