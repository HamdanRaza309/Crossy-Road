# 🐕 Crossy Road (Unity)

A 3D recreation of the classic **Crossy Road** built in **Unity** using C#. The project features procedural terrain generation, infinite gameplay, smooth grid-based movement, dynamic vehicle spawning, collision detection, and a responsive camera system.

This project was developed as an individual **Semester Game Jam Project**.

---

## 📖 Project Overview

Crossy Road is an endless arcade game where the player controls a character that must safely cross procedurally generated terrain while avoiding moving traffic. The game combines classic arcade gameplay with procedural generation techniques to create an infinite and replayable experience.

---

## 🎮 Gameplay

- Move using **WASD** or **Arrow Keys**
- Cross roads while avoiding moving vehicles
- Continue progressing forward through an infinite world
- Getting hit by a vehicle ends the game
- Restart and try to beat your previous progress

---

## ✨ Features

### Player
- Grid-based movement
- Smooth hopping animation
- Unity New Input System
- Collision detection
- Death state handling

### Procedural Generation
- Infinite terrain generation
- Grass lane generation
- Road lane generation
- Random tree placement
- Dynamic lane spawning

### Traffic System
- Vehicle spawning
- Multiple vehicle prefabs
- Lane-based traffic direction
- Adjustable vehicle speed
- Automatic vehicle cleanup

### Camera
- Orthographic camera
- Smooth camera follow
- Fixed isometric angle

### Game Systems
- Collision detection
- Game over system
- Restart functionality
- Death particle effects
- Terrain cleanup for performance optimization

---

## 🛠 Technologies Used

- Unity Engine
- C#
- Unity New Input System
- Unity Physics
- Coroutines
- Procedural Generation
- Orthographic Camera
- Particle System

---

## 📂 Project Structure

```
Assets/
│
├── Animations/
├── Materials/
├── Models/
├── Prefabs/
│   ├── Grass
│   ├── Road
│   ├── Trees
│   └── Vehicles
│
├── Scenes/
│
├── Scripts/
│   ├── PlayerMovement
│   ├── TerrainGenerator
│   ├── CameraFollow
│   ├── RoadSpawner
│   ├── Vehicle
│   └── GameManager
│
└── Particles/
```

---

## ⚙️ Core Systems

### Character Movement

- Grid-based movement
- Smooth hopping using Coroutines
- Input handled using Unity's New Input System

---

### Procedural Terrain

- Infinite lane generation
- Random grass and road spawning
- Random obstacle placement
- Dynamic map expansion

---

### Vehicle System

- Lane-specific vehicle spawning
- Continuous movement
- Alternating traffic directions
- Automatic despawning after leaving the map

---

### Camera System

- Orthographic projection
- Smooth follow movement
- Fixed isometric view

---

### Collision System

- Vehicle collision detection
- Player death handling
- Restart functionality using SceneManager

---

### Performance Optimization

- Destroy old terrain behind the player
- Remove off-screen vehicles
- Prevent unnecessary memory usage

---

## 🎯 Controls

| Key | Action |
|------|--------|
| W / ↑ | Move Forward |
| S / ↓ | Move Backward |
| A / ← | Move Left |
| D / → | Move Right |
| R / Space | Restart (After Death) |

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone <repository-url>
```

2. Open the project using Unity.

3. Open the main scene.

4. Press **Play**.

---

## 📚 Learning Outcomes

During this project I learned:

- Unity New Input System
- Grid-based movement
- Coroutines
- Procedural terrain generation
- Infinite level generation
- Camera follow systems
- Collision detection
- Particle systems
- Performance optimization
- Unity scene management

---

## 👨‍💻 Developer

**Hamdan Raza**

Department of Computer Science & IT

University of Engineering and Technology Peshawar

Registration Number: **22PWBCS0926**

---

## 📄 License

This project was developed for educational purposes as part of a university semester project.
