# Pranava Nadam (प्रणव नादम्)
### Sacred Sound and Visual Therapy Studio

**Pranava Nadam** is a self-contained, single-page procedural audio-visual consciousness, chakra, and brainwave entrainment web application built with **HTML5, CSS3, Web Audio API, and high-DPI HTML5 Canvas**. Every tone, noise floor, vocal-formant OM chant, and sacred geometry visual is generated mathematically in real time—with **zero external audio files** and **zero backend dependencies**.

---

## Core Highlights

- **100% Procedural Web Audio Engine (Tuned for IEMs)**
  - **4 Entrainment Delivery Modes:** Hard-panned **Binaural Beats** (default for IEM channel isolation), smooth raised-cosine **Isochronic Tones**, summed **Monaural Beats**, and **Pure Harmonic Drone** with toggleable sub-octave warmth.
  - **Sacred OM (`ॐ`) Formant Synthesizer:** Procedurally generated `136.1 Hz` vocal-formant `A-U-M` chanting loop with independent toggle and mix slider, opening directly on **Sahasrara (Crown Chakra)** after the safety notice.
  - **IEM Comfort & Hearing Safety DSP:** Low **18%** default master gain, mandatory **2.5-second click-free exponential fade-in/out** on play/pause/stop/preset switching, toggleable **60 Hz High-Pass Filter** on noise layers (prevents ear-canal pressure), and automatic **Low-Pass Warmth Softener** for high Solfeggio frequencies (`741 Hz+`).
  - **Procedural Masking Layers:** Real-time generated **Pink Noise** and **Brown Noise** with independent volume sliders.
- **60fps High-DPI Procedural Visuals & Zen Mode**
  - OLED-friendly `#000000` canvas with translucent glassmorphic controls that automatically fade out after **4 seconds of inactivity** into distraction-free **Zen Fullscreen Mode** (reappearing softly on pointer movement or tap).
  - **4-Stage Session Choreography:** Automatically evolves across **Arrival (0–10%)**, **Descent (10–25%)**, **Deep Immersion (25–90%)** driven by real-time `AnalyserNode` energy, and **Emergence (90–100%)**.
  - **Visual Comfort Controls:** Switch between **Eyes-Open Visuals** and **Eyes-Closed Soft Glow**, adjust the **10%–100% Brightness Dimmer**, and keep optional low-contrast **Rhythmic Visual Pulsing OFF by default**.
- **Flexible Session Timings & Auto-Ramp**
  - Choose **5 min**, **10 min**, **20 min**, **30 min**, **Unlimited (`∞`)**, or fine-tune from `5–60 min` via slider, with an optional **Auto-Ramp Entrainment Curve** (gliding from `12 Hz` Alpha to target over the first 5 minutes and optionally ramping back up at emergence).
- **On-Screen Practice Guide & Local Storage**
  - Every preset, chakra, and relief program updates a toggleable on-screen **Practice Guide** featuring an illustrated **Hand Mudra SVG**, finger-placement cue, **Fragrance / Aromatherapy**, **Bija Mantra**, and **Tantra / Breath Focus**.
  - Save, reload, and manage custom frequency configurations locally in `localStorage`.

---

## Built-In Suites

### 1. Brainwave & Altered-States Presets (9 Modes)
| Preset | Band / Frequency | Carrier | Visual Engine | Breathing Pacer |
| --- | --- | --- | --- | --- |
| **Deep Dreamless Sleep** | Delta (`2.5 Hz`) | `136.1 Hz` | Cosmic Nebula & Liquid Auroras | 4-7-8 Sleep Breath |
| **Hypnagogic & Lucid Dreaming** | Theta (`5.5 Hz`) | `174 Hz` | Rotating Flower of Life & Ripples | 5-6 Hypnagogic Breath |
| **Earth Grounding (Schumann)** | Schumann (`7.83 Hz`) | `136.1 Hz` | Toroidal Energy Field & Embers | 5.5s Coherence Breath |
| **Calm Flow & Open Awareness** | Alpha (`10 Hz`) | `200 Hz` | Ocean Horizon Wave Interference | Calm Wave Breath |
| **Still Body, Quiet Focus** | SMR (`14 Hz`) | `220 Hz` | Expanding Concentric Rings | 4-4-4-4 Box Breath |
| **Analytical Deep Work** | Beta (`18 Hz`) | `240 Hz` | 3D Rotating Metatron's Cube | 4-2-4 Clarity Breath |
| **Peak Cognitive & Compassion** | Gamma (`40 Hz`) | `256 Hz` | Live Mathematical Chladni Cymatics | Balanced Gamma Breath |
| **Ancient Chamber Trance** | `111 Hz` + `4.5 Hz` | `111 Hz` | Sacred Sri Yantra & Dust Motes | Chamber Resonance Breath |
| **9-Tone Solfeggio Suite** | `174`–`963 Hz` | Selectable | Morphing Lotus / Merkaba / Harmonograph | Harmonic Breath |

### 2. Seven Energy Centers (Chakras) Awakening Suite
Covers **Sahasrara** (`963 Hz` · `AUM`), **Ajna** (`852 Hz` · `OM`), **Vishuddha** (`741 Hz` · `HAM`), **Anahata** (`639 Hz` · `YAM`), **Manipura** (`528 Hz` · `RAM`), **Svadhisthana** (`417 Hz` · `VAM`), and **Muladhara** (`396 Hz` · `LAM`), each paired with its live procedural **Sacred Yantra**, **Bija Mantra**, **Tantra practice**, **Mudra diagram**, **Fragrance**, and traditional yogic endocrine correspondence.

### 3. Sound Vibration Comfort & Relief Suite (12 Programs)
Filterable complementary relaxation programs for **Head & Sinus** (tension headache, low-light migraine soothing, sinus pressure with Bhramari humming, nasal congestion/cold comfort, soft pink-noise tinnitus masking), **Body & Fever** (body aches, cooling fever rest, neck/eye strain, digestive calm), and **Mind & Sleep** (anxiety de-escalation, mental burnout reset, insomnia).

---

## Deploying to GitHub Pages

1. Rename the standalone application file (`pranava-nadam.html`) to `index.html` and place it alongside this `README.md` in your repository root:
   ```text
   pranava-nadam/
   ├── index.html
   └── README.md
   ```
2. Push to a public GitHub repository:
   ```bash
   git init
   git add index.html README.md
   git commit -m "Initial commit: Pranava Nadam — Sacred Sound and Visual Therapy Studio"
   git branch -M main
   git remote add origin https://github.com/<your-username>/pranava-nadam.git
   git push -u origin main
   ```
3. In your GitHub repository, open **Settings → Pages**, set **Source** to **Deploy from a branch** (`main` / `/ (root)`), and click **Save**. Your live studio will be available at `https://<your-username>.github.io/pranava-nadam/`.

### Running Locally
Simply open `index.html` in any modern desktop or mobile browser (Chrome, Edge, Safari, or Firefox). No build step or server is required.

---

## IEM Listening Recommendations

- **Disable Spatial Processing:** Turn off **Dolby Atmos**, **Apple Spatial Audio**, **Head-Tracking**, and surround virtualizers so Left and Right binaural oscillators remain 100% isolated.
- **Keep Volume Moderate:** Start at the default **18%** gain and adjust gently—entrainment works through subtle frequency perception, not loudness.
- **Use the 60 Hz High-Pass Filter:** Keep the 60 Hz HPF enabled in **DSP & Sandbox** if you use bass-heavy sealed IEMs to prevent sub-bass ear-canal pressure.

---

## Safety & Wellness Disclaimer

- **Photosensitivity & Seizures:** Do not use brainwave entrainment or visual geometry if you have epilepsy, a history of seizures, or photosensitive conditions. Rhythmic visual pulsing is disabled by default.
- **No Driving or Machinery:** Never listen to entrainment sessions while driving, cycling, or operating heavy equipment.
- **Complementary Wellness Only:** Sound frequencies, breathing pacers, mudras, aromatherapy, and traditional chakra/endocrine correspondences are intended strictly for relaxation, meditation, and personal comfort. They are **not medical treatments** and do not replace professional medical advice or care—please consult a qualified physician for severe migraines, high or persistent fever, or acute health conditions.

---

## Tech Stack

- **HTML5 & CSS3** (Tailwind CSS via CDN, responsive OLED dark glassmorphism)
- **Web Audio API** (Oscillators, `StereoPannerNode`, `BiquadFilterNode`, `AnalyserNode`, procedural noise buffers, formant synthesis)
- **HTML5 Canvas** (60fps high-DPI procedural sacred geometry, 3D projections, live Chladni cymatics)
- **Lucide Icons**

---
