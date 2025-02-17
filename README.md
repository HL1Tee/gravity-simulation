# 🌌 Extended Gravity Simulation

This project simulates a dynamic space environment with interactive celestial bodies. It includes gravitational interactions, object creation, and a visually appealing interface.

## 📷 Preview

![image](https://github.com/user-attachments/assets/c2a798d9-e832-4ccb-81bf-d99e2e94d2b6)

## 🚀 Features

- 🌍 **Dynamic Objects**: Planets, stars, black holes, asteroids, and comets with realistic gravity.  
- 🛠️ **Interactive Interface**: Control object properties and simulation speed.  
- 🔭 **Astronomer Mode**: Inspect object parameters in real-time.  
- 🪐 **Orbital Paths**: See the paths of orbiting objects.  

## 🎮 Controls

- 🖱️ **Left Mouse Button (LMB)**: Drag objects.  
- 🖱️ **Middle Mouse Button (MMB)**: Move the camera.  
- 🖱️ **Right Mouse Button (RMB)**: Lock the camera on a selected object.  
- 🔍 **Mouse Scroll**: Zoom in/out.  
- ⏸️ **Spacebar**: Pause/unpause the simulation.  
- ➕ **+/-**: Increase/decrease simulation speed.  
- 🔄 **0**: Reset simulation speed to normal.  

## ⚙️ UI Guide

- **Create Object**: Generate celestial bodies with custom parameters.  
- **Background Settings**: Switch between grid, stars, or a plain background.  
- **Time Control**: Adjust simulation speed.  
- **Pause Button**: Pause/resume the simulation.  
- **Orbit Toggle**: Show/hide orbital paths.  
- **Astronomer Mode**: Display object details on hover.  

## 🧠 Code Structure

### 1. `drawBackground()`
Handles background rendering:  
- Grid mode: Dynamic, scalable grid.  
- Star mode: Stars that move and scale with the camera.  
- Color can be adjusted in the UI.  

### 2. `updateSimulation()`
Calculates gravitational forces and updates object positions based on the time scale.  

### 3. `drawSimulation()`
Renders the background, objects, orbits, particles, and waves.  

### 4. `Planet` class
Represents celestial objects with properties like mass, radius, velocity, and optional rings.  

### 5. `Particle` class
Used for visual effects like collisions and comet tails.  

### 6. `handleCollisions()`
Detects and processes collisions by merging objects or spawning particles.  

### 7. `generateAstronomicalName()`
Generates random names like "AX-123" for celestial bodies.  

### 8. `spawnWave()`
Creates gravitational waves expanding from certain events.  

### 9. Camera System
The camera position and zoom level are managed based on user input.  

### 10. UI Event Handlers
Form submissions and button clicks for object creation, orbit toggling, and simulation speed adjustments.  

---

Made with 🚀, ☕️ and AI by [HL1Tee](https://github.com/HL1Tee) 
