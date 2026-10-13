# PC-Game-QA-Portfolio
PC Game QA Tester &amp; Bug Hunter | Lifelong PC gamer passionate about game feel, edge-case testing, and actionable bug documentation
# 🎮 Saad Javed | PC Game QA Tester

> *"PC Game QA Tester & Bug Hunter | Lifelong PC gamer passionate about game feel, edge-case testing, and actionable bug documentation."*

---

## 📫 Contact Information
* 📧 **Email:** saadjaved984@gmail.com
* 💬 **Discord:** saad_javed09
* 🕹️ **itch.io:** https://saadjaved09.itch.io

---

## 👨‍💻 About Me
I have been playing PC games since childhood, building a deep understanding of mechanics across FPS, Action/RPG, Strategy, and Indie genres. As a QA Tester, I channel that passion into structured exploratory testing, regression passes, and edge-case bug hunting. My goal is to save developers time by delivering clear Steps to Reproduce (STR) and media evidence for every issue found.

---

## 🖥️ Primary Testing Environment (PC Specs)
* **OS:** Windows 11 (64-bit)
* **CPU:** Ryzen 5 5600
* **GPU:** NVIDIA RTX 3080
* **RAM:** 16 GB RAM
* **Display:** 1920x1080 @ 60HZ
* **Peripherals:** Xbox Controller, Keyboard, Gaming Mouse

---

## 🛠️ QA Skills & Methodology
* **Functional & Regression Testing:** Verifying core mechanics and ensuring resolved bugs do not reoccur.
* **Exploratory & Edge-Case Testing:** Testing boundary limits (out-of-bounds, rapid inputs, resolution switching).
* **Clear Documentation:** Writing precise Steps to Reproduce (STR), assigning severity levels, and attaching media/logs.
* **UX & Game Feel Feedback:** Providing actionable notes on pacing, controls, and onboarding clarity.

---

## 🐛 Sample Bug Report

### [BUG-001] Character soft-locks when dashing into closing elevator doors
* **Game / Engine:** Sample Cyberpunk Runner (Unity WebGL / PC)
* **Severity:** High (Progress Blocking / Out of Bounds)
* **Frequency:** 4/5 times tested

#### 📋 Steps to Reproduce (STR)
1. Launch the game build and load Level 2 (Subway Station).
2. Approach the main elevator when the door-closing animation starts.
3. Perform a forward dash (`Shift` key) directly into the center seam of the closing doors.

#### 🔍 Expected Result
The player character collides with the door geometry or stops outside the elevator.

#### ❌ Actual Result
The player character clips through the door model and falls infinitely through the map floor.
