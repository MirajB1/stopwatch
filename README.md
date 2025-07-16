# 🕰️ Retro Calendar Stopwatch & Clock

> **Note:** _This is a personal project. I built it because I couldn't find anything online that matched exactly what I wanted._

A web-based stopwatch and clock with a **retro neon cyan aesthetic**, featuring subtle **flip animations**, **Gregorian and Nepali date displays**, and a **full-screen mode** that mirrors the standard view while hiding browser UI.

---

## ✨ Features

- **Stopwatch Mode**  
  Start, stop, and reset a timer displaying hours, minutes, and seconds.

- **Real-Time Mode**  
  Shows current time, toggled via a sidebar button.

- **Date Displays**
  - **Gregorian date** (e.g., _Jul 16, 2025_) and day (e.g., _Wednesday_).
  - **Nepali date** (e.g., _2082 Ashar 32_ for Jul 16, 2025, per **Bikram Sambat** calendar).

- **Subtle Flip Animation**  
  Digits flip upward with a smooth fade, designed to avoid distraction.

- **Full-Screen Mode**  
  Expands the entire interface (stopwatch, sidebar, dates) to fill the screen, hiding browser UI, with identical styling.

- **Retro Aesthetic**  
  Black background with neon cyan accents, inspired by vintage digital clocks.

---

## ▶️ Usage

1. **Open `stopwatch.html` in a modern browser** (e.g., Chrome, Firefox).

### ⏱️ Stopwatch Mode

- Click **Start** to begin timing.  
- Click **Stop** to pause.  
- Click **Reset** to clear the timer.

### 🕒 Real-Time Mode

- Click **Switch to Real Time** in the sidebar to show the current time.  
- Click **Switch to Stopwatch** to return to stopwatch mode.

### 🖥️ Full-Screen Mode

- Click **Full Screen** to expand the interface.  
- Click **Exit Full Screen** to return to normal view.

---

## ⚙️ Setup

- **No dependencies** — Single HTML file: `stopwatch.html`  
- Just save and open in a browser.  
- ⚠️ *Note: Full-screen mode requires user interaction (e.g., clicking a button) due to browser security policies.*

---

## 🗒️ Notes

- **Nepali date** for **Jul 16, 2025** is fixed as _2082 Ashar 32_.  
  Other dates use a simplified conversion:  
  - +56 years  
  - +8 months  
  - Max 32 days

- **Customize the flip animation**  
  Tweak the CSS `@keyframes flipIn` for different effects or timing.

---
