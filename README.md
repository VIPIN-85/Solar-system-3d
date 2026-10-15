# 🌌 OUR SOLAR SYSTEM — 3D Planetary & Live Earth Intelligence Engine

> **An interactive 3D astrophysical simulator and real-time Earth Digital Twin powered by Three.js, custom GLSL shaders, MediaPipe Computer Vision, Web Speech Voice Navigation, and Live Meteorological Telemetry.**

![Tech Stack](https://img.shields.io/badge/Three.js-r128-black?style=for-the-badge&logo=three.js)
![WebGL](https://img.shields.io/badge/GLSL-Custom_Shaders-008080?style=for-the-badge&logo=opengl)
![MediaPipe](https://img.shields.io/badge/MediaPipe-Hand_Tracking-10b981?style=for-the-badge)
![Status](https://img.shields.io/badge/Build-Single_File_Zero_Config-fbbf24?style=for-the-badge)

---

## ✨ Key Features

### 🪐 Complete Solar System with Exact Astrophysical Telemetry
* **The Sun + All 8 Planets + The Moon:** Explore **Sol**, **Mercury**, **Venus**, **Earth**, **Luna (Moon)**, **Mars**, **Jupiter**, **Saturn** (with icy ring systems), **Uranus**, and **Neptune**.
* **Authentic Orbital & Physical Constants:** Real equatorial radii ($\text{km}$), mean orbital velocities ($\text{km/s}$), axial tilts (including Earth's $23.44^\circ$ obliquity, Venus's retrograde spin, and Uranus's $97.77^\circ$ sideways roll), sidereal rotation periods, and surface gravities.
* **Tidally Locked Lunar Orbit:** The Moon orbits Earth at its exact $0.2727\times$ radius ratio while keeping its near hemisphere tidally locked toward Earth.

### 🌍 Real-Time Earth Sunlight, Sub-Pixel GLSL Terrain & Live Weather
* **Zero-Blur Sub-Pixel GLSL Shader:** Uses 5-octave 3D Fractal Brownian Motion (FBM) micro-topography and adaptive coastline sharpening so zooming close to beaches, mountain ridges, and oceans remains crisp without texture pixelation.
* **Live UTC Subsolar Point Lock:** Automatically calculates the Sun's real-time declination and subsolar longitude from your system's UTC clock—rendering Earth's exact day/night terminator, twilight scattering belt, and glowing night-side city lights right now.
* **Real-Time Weather Telemetry (Open-Meteo API):** Clicking or speaking any place on Earth fetches live local temperature ($^\circ\text{C}$), sky condition, wind speed ($\text{km/h}$), humidity ($\%$), cloud cover, and atmospheric pressure ($\text{hPa}$).

### 🎙️ AI Voice Navigation & Sideways "Explore" Intelligence Drawer
* **Voice-Activated Flight (`🎙️ Voice Assist`):** Speak any city, landmark, or planet (*"Ambala"*, *"New Delhi"*, *"Mount Everest"*, *"Tokyo"*, *"Saturn"*, *"Mars"*). The engine geocodes your command, flies the 3D camera directly to the target, and reads out an audio briefing.
* **Interactive AI Follow-Up Q&A (`🔭 Explore`):** Sideways glassmorphic intelligence drawer featuring live encyclopedic summaries, embedded high-resolution **Google Satellite** & **3D Google Earth** views, and a conversational follow-up bar (supports both voice and text questions).

### 🖐️ MediaPipe Webcam Hand-Tracking
* **Touchless 3D Navigation:** Control the planetary camera using real-time 21-point hand skeleton tracking:
  * **Pinch Close (Thumb + Index):** Pull back into deep orbital view.
  * **Spread Fingers:** Dive smoothly toward the planetary surface.
  * **Move Open Palm:** Orbit smoothly around the active planet or moon.

---

## 🚀 Quick Start

This entire engine is engineered as a **zero-dependency single-file application**.

1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/our-solar-system.git](https://github.com/YOUR_USERNAME/our-solar-system.git)
   cd our-solar-system
