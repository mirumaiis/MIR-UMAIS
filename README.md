# Antigravity Gaming // Defy Gravity. Dominate The Arena.

A futuristic, responsive, single-page website for **Antigravity Gaming** — an indie game studio and esports brand pioneering 6-DOF zero-gravity physics, tactical orbital combat, and deep-space extraction warfare.

---

## 🌌 Live Experience & Design Highlights

### Visual Aesthetic & Theme
- **Color Palette**: Deep space obsidian (`#07070D`), electric cyan (`#00F0FF`), ultraviolet / neon purple glows (`#8A2BE2` & `#BD00FF`), with crisp silver/white typography.
- **Typography**: Google Fonts — **Orbitron** (bold geometric display), **Syne** (sci-fi headings), and **Space Grotesk** (precision UI and body text).
- **Background Physics**:
  - 60 FPS HTML5 Canvas Starfield with cursor repulsion and dynamic constellation threads.
  - Faint 3D perspective cybernetic grid with depth masking.
  - Directional particle lift during Zero-G Mode.

---

## 🎮 Sections & Features

### 1. Floating Glassmorphic Navbar
- Frosted glass effect with `backdrop-blur-xl` and glowing cyber borders.
- Minimalist "Antigravity" logo with animated suspended orb SVG (spinning outer gyro ring, counter-rotating inner ring, and glowing core).
- Navigation links for **Games**, **Esports**, **Studio & Tech**, and **Community**.
- **Interactive Zero-G Mode Switch**: Real-time gravitational field toggle with animated indicators.
- **Web Audio API SFX Toggle**: Native sound effects engine (blips, zero-g warp tone, magnetic latch).
- **Play Now** glowing cyan button and fully responsive mobile drawer menu.

### 2. Interactive Zero-G Hero Section
- Full-viewport height (`min-h-screen`) featuring the headline: **"DEFY GRAVITY. DOMINATE THE ARENA."**
- **Centerpiece Visual**: A floating holographic HUD card cluster and quantum gyro artifact that reacts to mouse position with smooth **3D Parallax tilt & shift**.
- Real-time telemetry badges: Gravitational vector `[0, 0, 0] m/s²`, orbital velocity `27,450 km/h`, and active pilots counter.
- Dual CTAs: **"Explore Games"** and **"Watch Showreel"** (triggers cinema modal).

### 3. Featured Games Showcase (Bento Grid)
Includes 3 flagship titles with custom SVG artwork, lore, genre badges, and platform tags:
1. **ORBITFALL: BREACH ZERO** — Tactical 6-DOF Zero-G Shooter (PC, PS5, Xbox Series X).
2. **ZERO-G DRIFT: APEX VELOCITY** — Anti-Matter Hyper-Racing at 1,400 km/h (PC, PS5 VR2, Quest 3).
3. **NEBULA PROTOCOL: VOID HARVEST** — Deep-Space Extraction Survival RPG (Steam, Epic Games).
- **Singularity 4.0 Physics Sandbox**: An interactive mini-canvas where users can click to spawn gravitational mass points and watch micro-satellites slingshot in real time!
- **Global Low-Latency Netcode Grid**: Live ping matrix showing sub-15ms edge relay nodes across Tokyo, Frankfurt, and US-East.

### 4. Esports & Live Arena Hub
- **Simulated Live Twitch Player**:
  - Live broadcast frame with viewer count (`52,800+ viewers`) and low-latency tag.
  - 2D Canvas action simulation featuring combat drone vector duels and live kill feed (`VTX.KAIZEN [RAILGUN] ECL.VOX`).
  - Animated live Twitch chat stream ticker with real-time spectator hype.
- **Championship Countdown Timer**: Real-time ticker counting down Days, Hours, Minutes, and Seconds to the $1,250,000 World Cup Grand Finals.
- **Upcoming Match Schedule**: Live stage bracket showing Vortex vs Eclipse 9 (Map 3 Overtime), Nova Syndicate, and open qualifier registration.

### 5. Interactive "Zero-G Mode" Easter Egg
- Activating the **Zero-G toggle** in the navbar triggers an instantaneous shift in physics:
  - All cards, badges, buttons, and HUD telemetry lose gravity, smoothly detaching and floating upwards by -20px to -45px.
  - Multi-frequency sinusoidal bobbing keyframes (`zeroGBob`) at staggered delays simulate genuine weightless buoyancy.
  - Hovering over floating cards adds an extra impulse vector, allowing users to "nudge" objects floating in mid-air.
  - A warning banner slides in: `WARNING: ZERO-G MATRIX ENGAGED // INERTIAL DAMPENERS OFFLINE`.
  - The canvas starfield particles transition from subtle drift to upward freefall.
  - Web Audio synthesizes deep space sub-bass resonance and crystal shimmers.
  - Toggling off smoothly restores 1.0G standard gravity with a magnetic clamp sound effect.

### 6. Studio & Proprietary Tech Division
- Highlights the **Singularity 6DOF Physics Stack**: Dual-quaternion interpolation, sub-quantum rollback netcode, and atmospheric decompression velocity simulation.
- Studio metrics: 42 core devs across 14 countries and 9 physics patents.

### 7. Community & Newsletter ("Join The Orbit")
- Cyber terminal newsletter input with transmission verification and status feedback.
- Social links: Discord (54,000+ members), Twitch, X (@AntigravityGG), and YouTube.

### 8. Showreel / Trailer Cinema Modal
- Full-screen cyberpunk theater with custom hyperspace warp canvas animation, targeting reticles, recording timecode, and playback controls.

---

## 🛠️ Tech Stack & Architecture

- **Semantic HTML5**: Clean structure with high accessibility standards.
- **Tailwind CSS (via CDN)**: Fully customized design tokens (colors, animations, keyframes, box shadows, glassmorphism).
- **Vanilla JavaScript**:
  - 60 FPS HTML5 Canvas particle & starfield engine.
  - 3D perspective mouse parallax with linear interpolation (lerp).
  - Interactive mini gravity well simulation.
  - Real-time tournament countdown timer.
  - Web Audio API Sound Synthesizer (pure procedural audio, zero external audio assets).
- **Inline SVG Graphics**: Handcrafted sci-fi illustrations for game covers, holographic gyro rings, and status badges.

---

## 🚀 How to Run & Preview

Simply open `index.html` in any modern web browser:
- **Direct file access**: Double-click [index.html](file:///c:/Users/acer/Documents/MIR%20UMAIS/index.html) or right-click -> "Open with Chrome / Edge / Firefox".
- **Local HTTP server** (optional):
  ```bash
  # Using Python
  python -m http.server 8080
  # Then open http://localhost:8080 in your browser
  ```

---

*© 2026 Antigravity Gaming Studios Inc. All Rights Reserved.*
