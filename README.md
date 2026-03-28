# 🌍 Atmospheric Weather 3D
**A high-fidelity, interactive 3D weather experience built with Three.js and the OpenWeatherMap API.**

[Live Demo](https://maytri315.github.io/weather/)

---

## ✨ Overview
Atmospheric Weather is a visual-first utility that replaces static data with a cinematic 3D environment. It features a realistic, interactive Earth that transitions from deep space into a polished UI, providing real-time weather insights alongside context-aware lifestyle recommendations.

## 🚀 Key Features

### 1. **Cinematic 3D Engine**
* **Interactive Earth**: A realistic 3D model utilizing high-resolution textures, normal maps for topography, and specular maps for water reflections.
* **Atmospheric Layering**: A dynamic, semi-transparent cloud layer that rotates independently of the Earth's surface.
* **Fluid Entrance Animation**: A JavaScript-driven camera transition that moves from a "deep space" perspective to a focused UI view upon loading.

### 2. **Ultra-Premium UI/UX**
* **Glassmorphic Interface**: A multi-layered glass card featuring high-saturation backdrops, blur filters, and 3D tilting effects that respond to mouse movement.
* **Responsive 3D Layout**: A perspective-aware design that maintains its aesthetic across both desktop and mobile devices.
* **Dynamic 3D Icons**: High-quality fluency icons that represent weather conditions with "Ultra-Float" animations.

### 3. **Smart Logic & Personality**
* **Contextual Recommendations**: Instead of generic advice, the system suggests activities like fixing Python bugs, working on digital art, or heading out for street food based on live conditions.
* **Real-time Data**: Global accuracy for temperature, humidity, and wind speed powered by the OpenWeatherMap API.
* **Error Resilience**: Custom-handled error states for unrecognized locations.

## 🛠️ Technologies Used
* **Three.js**: WebGL-based 3D graphics and animations.
* **JavaScript**: Logic for API integration and camera movements.
* **HTML5 & CSS3**: Modern layout using Flexbox, Grid, and Glassmorphism effects.
* **OpenWeatherMap API**: Real-time meteorological data source.

## 🏗️ Getting Started

1.  **Clone the repository**:
    ```bash
    git clone [https://github.com/maytri315/weather.git](https://github.com/maytri315/weather.git)
    ```
2.  **Setup API Key**:
    Open `index.html` and replace the `apikey` constant with your OpenWeatherMap key.
3.  **Launch**:
    Open `index.html` in a browser. For best results with texture loading, use a local server (like VS Code Live Server).

---
Developed with 💙 by [Maytri Shah](https://github.com/maytri315)
