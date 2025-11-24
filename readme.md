Cosmic Geometry Visualizer

A cyberpunk-style 3D music visualizer built with Three.js, Web Audio API, and GPU-accelerated particle shaders.
Upload any audio file and watch it morph into dynamic mathematical shapes — galaxies, fractals, attractors, helixes, and more.

This project uses custom GLSL shaders, audio-reactive particle displacement, and interactive shape morphing to create a fully immersive visualization experience.

🚀 Features
🎧 Audio-Reactive Visuals

Upload your own MP3/WAV/etc. files

Auto-analyzes beat + low-frequency energy

Particle system reacts with:

Pulse size

Explosion intensity

Color flashing

🌌 Multiple Mathematical & Cyber Shapes

Smoothly morph between any of the following:

Audio DNA (default)

Galaxy Spiral

Lorenz Attractor

Mobius Strip

Klein Bottle

Descartes Heart

Menger Sponge

Sierpinski Fractal

Penrose Triangle

Cyber Grid

Each shape contains 35,000+ GPU particles rendered with additive blending.

✨ Custom Shader System

Noise-based displacement

Beat-driven explosive pulses

Glow particles

Additive blending

Smooth 0→1 morph transitions

Cyberpunk cyan–magenta gradient colors

🧪 lil-GUI Controls

Fine-tune visuals in real time:

Particle size

Fractal noise level

Beat pulse

Explosion force

Color reaction

Shape selection

🎛 Playlist Support

Upload multiple audio files

Auto playlist rendering

Click to jump to a track

Auto-next on song end

Displays current track name & shape

🛠 Tech Stack

Three.js

GLSL (custom vertex + fragment shaders)

Web Audio API

lil-GUI

Vanilla JavaScript + HTML + CSS

No bundlers or frameworks required — works in any modern browser.

📦 How to Run
1. Clone or download
git clone <your-repo-url>

2. Open directly in browser

Just open:

index.html

3. (Optional) Serve locally

If you prefer a local server:

npx http-server .


or:

python3 -m http.server

🎮 How to Use

Click UPLOAD MUSIC and select audio files

Select a geometric shape from the GUI

Watch particles morph + react to the beat

Orbit around using your mouse / trackpad

Tweak the parameters live in the panel

🧩 Project Structure
index.html            # Main file (HTML + CSS + JS)
├── three.js          # CDN import
├── OrbitControls     # Camera control
└── lil-gui           # UI panel


The entire visualizer is contained in a single HTML file.

🔮 Future Enhancements

Bloom/Glare post-processing

Color themes (Neo Tokyo / Aurora / Deep Space…)

Microphone input mode

Export-to-image

Record visualizer video

WebXR/VR support

📜 License

MIT License — free to modify and redistribute.