# 🎵 Audio Visualizer

A minimal, beautiful, and animated audio visualizer built with pure HTML, CSS, and JavaScript. Watch music come to life with smooth animations and multiple visualization styles.

![Audio Visualizer](https://via.placeholder.com/800x400/0a0e27/00ff9d?text=Audio+Visualizer)

## ✨ Features

- **4 Visualization Styles:**
  - 🎚️ **Bars** — Classic equalizer bars
  - 🔵 **Circle** — Radial particle animation
  - 〰️ **Wave** — Smooth waveform visualization
  - 🌸 **Flower** — Petal-based animation

- **Customization:**
  - 🎨 Custom color picker
  - ⚡ Sensitivity slider
  - 🎚️ Real-time adjustments

- **Controls:**
  - ▶️ Play/Pause button
  - ⏹️ Stop button
  - Switch visualization styles instantly

- **Design:**
  - 🌙 Dark minimal aesthetic
  - 💫 Smooth animations
  - 📱 Responsive design
  - ⚡ Zero dependencies

## 🚀 How to Use

### Option 1 — Single File (Easiest)
1. Download `audio-visualizer.html`
2. Double-click to open in any browser
3. Click **▶ PLAY** button
4. Watch the visualization!
5. Switch styles anytime

### Option 2 — Copy & Paste
1. Copy the HTML code
2. Create new file → Save as `index.html`
3. Double-click to open
4. Done!

### Option 3 — GitHub Pages
1. Push to GitHub repository
2. Enable GitHub Pages in settings
3. Live at `https://yourusername.github.io/audio-visualizer`

## 🎯 Visualization Styles

### 1. Bars (Default)
- Classic equalizer style
- Vertical bars responding to frequency
- Perfect for music with strong bass

### 2. Circle
- Radial particles orbiting center
- Particles expand with intensity
- Great for techno/EDM

### 3. Wave
- Smooth continuous waveform
- Filled area under the curve
- Best for melodies

### 4. Flower
- Petal-like particles radiating outward
- Organic, flowing animation
- Perfect for ambient music

## 🛠️ Tech Stack

| Technology | Purpose |
|-----------|---------|
| HTML5 | Structure |
| CSS3 | Styling, dark theme |
| Canvas API | Real-time visualization |
| Web Audio API | Audio frequency analysis |
| JavaScript ES6+ | Animation logic, interactivity |

## 📋 Features Explained

### Web Audio API
- Creates demo audio (sine wave oscillator)
- Analyzes frequency data in real-time
- No external audio files needed

### Canvas Animations
- `requestAnimationFrame` for smooth 60fps
- Real-time drawing of 4 different visualizations
- Dynamic color and sensitivity adjustments

### Responsive Design
- Works on desktop, tablet, mobile
- Canvas scales with window size
- Touch-friendly controls

## 🎨 Customization

### Change Default Color
Find this line in code:
```html
<input type="color" id="color" value="#00ff9d" ...>
```
Change `#00ff9d` to any hex color.

### Adjust Default Sensitivity
Find this line:
```html
<input type="range" id="sensitivity" min="0.5" max="3" step="0.1" value="1.5">
```
Change `value="1.5"` to higher (more intense) or lower (subtle).

### Change Background Color
Find this in style:
```css
body{background:#0a0e27; ...}
```
Replace `#0a0e27` with your color.

## 📁 File Structure
