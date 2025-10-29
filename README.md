# 🌌 Quantum Canvas Ultimate — Universal Physics & Music Engine v5.0

Quantum Canvas Ultimate is a web application that creates a real-time, symbiotic experience between audio synthesis and 3D particle physics visualization. Musical parameters (tempo, scale, effects) influence the 3D particle system while physics metrics influence color, speed, and particle movement.

---

![Uploading Screenshot 2025-10-29 160832.png…]()


## 🚀 Key Features

- Unified engine
  - Real-time symbiosis: musical parameters and physics run together — tempo, scales, and effects can directly influence particle motion while physics metrics influence audio/visual mapping.
  - Audio/Video recording: capture sessions as synchronized `.webm` video files (visuals + audio).

- Physics & visuals
  - Multiple physics models: Lorenz & Rössler attractors, orbital gravity, flocking (Boids), vortex dynamics, and more.
  - Procedural patterns: Fibonacci spiral, DNA double helix, Mandelbrot set, cube lattices, and other starting formations.
  - Customizable particles: spheres, cubes, tetrahedrons, stars — control count, size, glow, material and emissive properties.

- Music & sequencing
  - 16-step pattern sequencer for rhythmic and melodic loops.
  - Pattern modes: melody, harmony/chords, filter modulation, visual/physics triggers.
  - Advanced scales: Pentatonic, Dorian, Japanese, Arabic, plus configurable root note and octave.
  - Interactive virtual keyboard for live play.

- Evolutionary engine (genetic algorithm)
  - Automatically tune parameters by fitness criteria (particle behavior, color aesthetics, pattern discovery).
  - Runs generations periodically to evolve configurations.

---

## 🛠️ Technology Stack

- Single-file HTML / JavaScript / CSS web application (designed for performance and portability).
- 3D visualization: Three.js (R128) for rendering and physics-driven particle systems.
- Audio synthesis: Tone.js for polyphonic synthesis, ADSR envelopes, effects (filter, reverb, delay, distortion, chorus) and real-time analysis.
- Styling: custom CSS inspired by LCARS (Library Computer Access/Retrieval System).

---

## 📝 How to use

### A. Getting started
1. Open the app in a modern browser.
2. Click the ▶ START button in the center panel to initialize the Tone.js audio engine. The AUDIO ENGINE indicator will turn green.
3. Playback begins using the current 16-step pattern and the Tempo setting.

### B. Configuring physics
1. Open the PHYSICS tab (right panel).
2. Select a physics model (e.g., Lorenz attractor, flocking).
3. Adjust Force Strength and Damping to control chaos vs. stability.
4. Use Audio Reactivity to control how audio analysis (volume/frequency) influences the physics simulation.

### C. Creating patterns
1. Open the PATTERN SEQUENCER (left panel).
2. Click RANDOM to generate a new 16-step pattern, or toggle individual steps (0 / 1 cells).
3. Select a Pattern Mode to decide what the sequence controls:
   - Melody: plays notes from the selected scale.
   - Harmony / Chords: plays chord voicings based on the root note.
   - Filter modulation: automates the synthesizer filter cutoff.
   - Visual / Physics / Color: triggers visual or physical parameter changes.

### D. Advanced functions
- Presets: load curated presets (e.g., Ambient Space, Quantum Field) to apply preconfigured audio + visual parameter sets.
- Interactive keyboard: click the 🎹 KEYBOARD button in the footer to open an overlay piano and play along.
- Recording: press ⚫ RECORD to start capturing audio + visuals; press ■ STOP REC to stop and download a synchronized `.webm` file.

---

## 🧬 Evolutionary engine tips

- Mode selection: choose the evolution target (Particle Behavior, Color Evolution, Pattern Discovery) to focus the optimization.
- Timing: evolution runs periodically (by default one generation every ~2 seconds). Monitor the Best Fitness value for convergence.
- Control: use EVOLVE to start and STOP to pause and lock a configuration you like.

---

## Presets and examples

Include any built-in presets or example configurations you want users to try. If you have screenshots or short GIFs, add them here for visual reference.

---

## Development notes

- Single-file distribution makes it easy to host anywhere (raw HTML file, GitHub Pages, or a local file).
- For serious experimentation, consider extracting modules (audio, physics, UI) into separate files for maintainability and testing.

---

## License

Specify your preferred license here (for example: MIT).
