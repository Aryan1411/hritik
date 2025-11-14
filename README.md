# Hritik Sharma — Portfolio

MIT Licensed single‑page portfolio for Hritik Sharma, an Aerospace Engineer and Astronaut. It features an aesthetic, performant background with animated rockets flying and orbiting, plus a theme toggle for Night and Day.

## Overview
- Elegant, responsive, and fast: no external assets or build steps.
- Interactive animated background:
  - Night: twinkling stars, gradient planets (one with a ring), orbiting rockets, and periodic rocket launches with exhaust.
  - Day: blue sky gradient with a glowing sun and drifting clouds; satellites/rockets still fly.
  - Launch your own rocket via the “Launch Rocket” button or “L” key.
- Theme toggle:
  - Switch between Night and Day. Accessible button with clear label and state, and preference persisted in localStorage.
- Content sections:
  - Hero, About, Experience, Core Skills, Missions/Projects, and Contact (demo form).
- Accessibility and performance:
  - Respects “prefers-reduced-motion” (pauses animation and renders a static scene).
  - System fonts, no network calls, scales to device pixel ratio for crisp rendering.

## Setup
No build tools required.

- Option 1: Double‑click index.html to open in your browser.
- Option 2: Serve locally (recommended for best canvas performance):
  - Python: python3 -m http.server 8000
  - Node (serve): npx serve
  - Open http://localhost:8000 (or the port printed by your server).

## Usage
- Use the sticky header to jump between sections.
- Press “L” or click “Launch Rocket” to spawn a rocket with animated exhaust.
- Click the “Night/Day” toggle to switch themes. Your choice is saved for the next visit.
- Fill the contact form and click Send to see a demo alert (replace with your backend as needed).

## Improvements in Round 2
- Added continuous background rocket animation:
  - Periodic rocket launches from the horizon with exhaust particles.
  - Orbiting rockets around celestial bodies.
  - Device‑pixel‑ratio aware rendering for crisp visuals.
- Added theme toggle button for Night/Day:
  - Night theme with stars and planets; Day theme with a sun and drifting clouds.
  - Accessible control (aria‑pressed, descriptive label) and persistence via localStorage.
- Enhanced accessibility and performance:
  - Respects prefers‑reduced‑motion by disabling animation and rendering a static scene.
  - Kept everything inline and dependency‑free for faster loads.

## License
MIT License

Copyright (c) 2025 Hritik Sharma

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.