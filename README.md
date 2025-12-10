# Tank Battle 3D

![OpenGL](https://img.shields.io/badge/OpenGL-3D%20Game-blue) 
![License](https://img.shields.io/badge/License-MIT-green)

A **3D tank battle game** built with Python and OpenGL. Navigate the battlefield, destroy enemy tanks, dodge obstacles, and manage your health and accuracy.

This project was developed as the final lab project for **CSE423 Computer Graphics**.

---

## 👥 Credits & Project Details

**Course:** CSE423 (0.75 Credit Lab)  
**Supervised by:** 
* Farhan Feroz [FHZ]
* Arian Nuhan [CARN]

**Developed by:**
* **[Md. Tanvirul Islam](https://github.com/Tanvir3141592)**
* **[Monowar Husain](https://github.com/MonowarHusain)**
* **Al Mahmud**
---

## Features

- 🛡 **3D Graphics** — Rendered with OpenGL, featuring dynamic camera perspectives.
- 🤖 **Enemy AI** — Enemy tanks pursue you and retreat upon collision.
- 🌳 **Obstacles** — Trees and houses block movement and bullets.
- 💥 **Explosions** — Visual and particle effects when enemies are destroyed.
- 🎥 **Camera Modes** — Toggle between first-person and third-person views.
- 🔧 **Cheat Mode** — Auto-rotation and rapid fire (for testing or fun).
- ⚡ **Power-ups** *(planned)* — Health boosts, rapid fire upgrades, and shields.

---

## Controls

| Action         | Keys/Mouse                                   |
|---------------|---------------------------------------------|
| **Move**      | `W` (forward), `S` (backward), `A` (rotate left), `D` (rotate right) |
| **Turret**    | `Q` (rotate left), `E` (rotate right)       |
| **Shoot**     | Left-click                                   |
| **Camera**    | `V` (toggle first-/third-person), Arrow keys (adjust distance/height) |
| **Cheats**    | `C` (toggle auto-rotation + rapid fire)     |
| **Restart**   | `R` (after game over)                       |

---

## Installation

### Requirements

- Python 3.x  
- Packages: `PyOpenGL`, `PyOpenGL_accelerate`, `GLUT`

### Install Dependencies

```bash
pip install PyOpenGL PyOpenGL_accelerate
