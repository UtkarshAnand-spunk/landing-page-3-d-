D Iridescent Typography Scene
An interactive web-based 3D scene built with Three.js featuring a high-fidelity iridescent torus and dynamic 3D typography.
This project demonstrates advanced material properties like iridescence, transmission, and physical-based rendering (PBR).

🚀 Features
Iridescent Torus: A central 3D torus utilizing MeshPhysicalMaterial to simulate realistic light interference and glass-like transparency.

3D Typography: Dynamic rendering of the text "CODEPEN" using TextGeometry and an external typeface loader.

Real-time Debug GUI: An integrated lil-gui panel allowing users to live-tweak material properties such as metalness, roughness, and IOR (Index of Refraction).

Dynamic Lighting: A complex lighting setup consisting of an ambient light and four strategically placed point lights to highlight material reflections.

Responsive Design: A full-screen WebGL canvas that automatically scales with the browser window.

🛠️ Technologies Used
Three.js (v0.182.0): The core 3D engine used for rendering.

lil-gui: A lightweight controller library for real-time parameter manipulation.

ES Modules: Modern JavaScript syntax using importmap for dependency management.

CSS3: For layout and overflow management.

📁 Project Structure
index.html: The entry point containing the canvas element and the Three.js import map.

style.css: Stylesheet for full-screen canvas positioning and background styling.

design.js: The main logic file handling scene creation, object geometry, materials, and the animation loop.

⚙️ Setup & Installation
Clone the files: Ensure index.html, style.css, and design.js are in the same directory.

Local Server Requirement: Due to the use of ES Modules and external font loading, this project cannot be run by simply opening index.html in a browser.

You must use a local server (e.g., VS Code Live Server extension, Vite, or Python's http.server).

Launch: Open the local server address (usually http://localhost:5500) in your browser.
