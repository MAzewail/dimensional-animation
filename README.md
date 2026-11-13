# Perspective Dimensional Shift: 0D Point to 3D Volume Animation

An interactive, cinematic WebGL/Three.js 3D animation exploring geometric dimensional emergence and perspective revelation.

## The Progression Narrative

1. **Stage 1 (0D — The Point):**
   A solitary glowing point floating in empty space. In zero dimensions, it possesses pure coordinates with zero length, width, or depth.
2. **Stage 2 (1D — The Line Segment):**
   Upon click, the perspective tracks back to reveal that this point was actually the terminus (End Point) of a 1-dimensional line segment drawn backward through space.
3. **Stage 3 (2D Space — Coordinate Grid):**
   A 2D coordinate grid emerges, demonstrating that the line exists within a quantifiable reference plane.
4. **Stage 4 (Vector Direction — The Starting Point):**
   The opposite end illuminates in contrasting neon rose/coral, anchoring the line between a definite Start and End point with direction and length.
5. **Stage 5 (Perspective Shift — Planar Surface):**
   The camera performs an orbital sweep up to an angle, revealing a stunning revelation: what appeared to be a 1D line was actually the razor-thin edge of an illuminated 2D planar sheet viewed edge-on!
6. **Stage 6 (3D Volume — Array of Planes Forming a Cube):**
   The plane is revealed to be one slice of an array of parallel planes stacked along the vertical axis, assembling an entire 3D volumetric square/cube in space with full 3D orbital inspection.

## Features & Controls

- **Interactive Navigation:**
  - **Click anywhere on the canvas** or press <kbd>Space</kbd> / <kbd>→</kbd> to advance to the next revelation.
  - Press <kbd>←</kbd> to step backward.
  - Interactive clickable step indicators (0D, 1D, 2D, PT, Surface, Cube) in the bottom control dock.
  - Press <kbd>R</kbd> to replay from Stage 1.
- **3D Free Orbit Mode:**
  - Toggle with <kbd>O</kbd> or click the **3D Orbit** button in the top right to freely drag, rotate, and zoom the camera around the 3D structures.
- **Auto-Play Presentation Mode:**
  - Toggle with <kbd>A</kbd> or click **Auto Play** to let the animation smoothly cycle through every dimensional revelation automatically (great for talks and recordings).
- **Audio Feedback:**
  - Synthesized Web Audio harmonic chimes on every dimensional transition (toggle with <kbd>M</kbd> or click the Audio button).
- **Direct Stage Deep Linking:**
  - Append `?step=0`, `?step=1`, ..., `?step=5` to the URL to jump directly to any specific dimensional revelation.

## How to Run

Simply open `index.html` in any modern web browser:
```bash
# Direct browser launch
google-chrome dimensional-animation/index.html
# or with python local server
python3 -m http.server 8000
```
Then visit `http://localhost:8000/dimensional-animation/index.html`.

