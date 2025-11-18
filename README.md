# Vortex — Stopwatch Web Application

Vortex is a front-end stopwatch project built using HTML, CSS, and JavaScript.  
It provides precise time tracking with lap recording, keyboard shortcuts, responsive UI design, and a polished animated interface.

## Live Demo
https://parthp137.github.io/PRODIGY_WD_02/

---

## Features

### Stopwatch
- Start, pause and reset the timer
- Accurate millisecond tracking using `performance.now()` and `requestAnimationFrame`
- Lap time recording and lap counter
- Persistent state using `localStorage` (laps and elapsed time survive page reload)

### Keyboard Shortcuts
- **Space** — Start / Pause  
- **Enter** — Record lap  
- **L** — Record lap  
- **R** — Reset

### UI / UX
- Large centered timer display
- Animated background and neon accents
- Lap drawer on the home page and a dedicated Laps page
- Smooth transitions, ripple click effect and subtle visual polish
- Responsive layout and mobile-friendly navigation

### Laps & Export
- Laps shown in ascending order (Lap 1 = oldest)
- Copy laps to clipboard
- Export laps as CSV

---

## Tech Stack
**Frontend:** HTML, CSS, JavaScript  
**Tools:** VS Code, Git, GitHub Pages

---

## Design Overview
The app uses a modern, dark theme with glass-morphism cards and neon accent colors.  
Main design goals: clarity, responsiveness, and a focus on precise timing UX.

Primary UI elements:
- Centered stopwatch card with large readable digits  
- Lap drawer pinned to bottom on the Home page  
- Dedicated `laps.html` page for full-screen lap management  
- Fixed top navigation with smooth scrolling and active state

---

## Limitations
- No backend; data is stored only in browser `localStorage`  
- Laps are local to the device/browser (no cross-device sync)  
- No user accounts or server-side persistence

---

## Future Enhancements
- Real-time sync between tabs/devices (cloud storage)  
- Per-lap edit/delete actions  
- Countdown and split-time modes  
- Export to JSON / Excel  
- Theme toggle (Light/Dark) and accessibility improvements

---

## Project Structure
├── index.html # Main stopwatch page

├── laps.html # Full-screen laps page

├── style.css # Styling, animations, layout

├── script.js # Stopwatch logic and interactivity

├── images/ # Backgrounds & assets (optional)

└── README.md

## How to Run

### 1. Clone the repository:

git clone https://github.com/parthp137/PRODIGY_WD_02.git
cd PRODIGY_WD_02

### 2. Open the project in a browser:
- Open `index.html` directly, or

### 3. Start a local server:
python -m http.server 8000

shell
Copy code

### 4. Open your browser and visit:
http://localhost:8000
