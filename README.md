# Presentation Drill — Teacher Lewis

A single-file HTML app that guides students through a structured spoken presentation and records their voice.

## What it does

- Gives the student a **random topic** from four difficulty categories (Everyday, Business, Finance, Big Ideas)
- Guides them through a **7-section presentation structure** with a live countdown timer for each phase:
  - Introduction (30s)
  - Point 1 (40s) → Transition (10s)
  - Point 2 (40s) → Transition (10s)
  - Point 3 (40s)
  - Conclusion (30s)
- **Records the full session** using the browser microphone (MediaRecorder API)
- Shows a **visual structure map** that highlights the current section in real time
- On finish: plays back the recording with options to **download**, **share**, or **copy the structure**

## How to use

1. Open `feedback.html` in any modern browser (Chrome recommended)
2. Choose a topic difficulty and click **Get My Topic**
3. Take 20 seconds to plan, then click **I'm Ready — Start Recording**
4. Speak through each section as guided — the timer advances automatically
5. Listen back and download your recording

## Settings

Click the ⚙ gear icon on the start screen to customise the time for each section.

## No install required

Single HTML file — no dependencies, no server, no build step. Works offline after first load (fonts require internet).

## Built for

English speaking practice with [Teacher Lewis](https://preply.com) on Preply.
