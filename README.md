# MYTECH Career Fair Lucky Draw 🎡

![Animated Prize Wheel](assets/wheel_spin_demo.webp)

A professional, high-performance, and visually stunning wheel spinner web application designed specifically for the MYTECH Career Fair. Built to handle large numbers of participants with smooth animations, immersive sound effects, and an engaging user experience.

## ✨ Features

- **High-Performance Canvas Rendering:** Capable of seamlessly rendering over 100+ names with buttery smooth frame rates using off-screen caching.
- **Dynamic Camera Zoom:** The wheel automatically scales and zooms into the pointer during the spin to build suspense and maximize readability.
- **CSV Data Import:** Able to directly import CSV files and it will auto-generate the namelist.
- **Immersive Audio:** Utilizes the Web Audio API to synthesize rhythmic ticking, drum rolls, and a triumphant fanfare sound effect without requiring external audio files.
- **Idle Animation:** Features a gentle, continuous idle rotation when not in use to attract attendees to the booth.
- **Celebration Effects:** Triggers a beautiful confetti particle system and a professional modal popup when a winner is drawn.
- **Responsive Design:** Automatically scales to fit any screen size, making it perfect for both large displays and tablets.

## 🚀 How to Use

1. **Open the Application:** Simply open `index.html` in any modern web browser (Chrome, Firefox, Safari, Edge).
2. **Load Participants:** Paste your participant names (or CSV text) directly into the input area. The application will automatically detect and parse the list.
3. **Generate the Wheel:** Click "Generate Lucky Draw" to build the wheel.
4. **Spin to Win:** Click anywhere on the wheel or press the `Spacebar` to initiate a spin.
5. **View Results:** The wheel will zoom in, draw a winner, and display their name. Closing the popup automatically removes the winner from the list so they cannot be drawn twice.
6. **Reset:** Use the "Reset" button to clear the current session and start over.

## 💻 Technologies Used

- **HTML5 Canvas:** For high-performance rendering of the wheel and confetti physics.
- **Vanilla JavaScript (ES6+):** Pure logic handling without any heavy external libraries.
- **Web Audio API:** For synthesizing real-time, procedural sound effects.
- **Vanilla CSS:** Custom properties, flexbox/grid layouts, and glassmorphism styling.

## 🏆 Credits

**Created by Tiong Tsui Jeff for MYTECH Career Fair.**
