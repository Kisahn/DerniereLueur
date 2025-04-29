# 🕯️ Dernière Lueur – 3D Contemplative Prototype

📘 This project is also available in French: [Lire en français 🇫🇷](./README_FR.md)

---

## 📑 Table of Contents
- [Introduction](#-dernire-lueur--3d-contemplative-prototype)
- [🎮 Key Features](#-key-features)
- [🧱 Technologies Used](#-technologies-used)
- [👥 Development Team](#-development-team)
- [🔗 LinkedIn Profiles](#-linkedin-profiles)
- [📦 Final Build](#-final-build)
- [📥 Repository Requirements](#-repository-requirements)
- [🧪 Learning Objectives](#-learning-objectives)
- [🔍 Full Walkthrough](#-full-walkthrough)
- [📜 License](#-license)

---

# 🕯️ Dernière Lueur – 3D Contemplative Prototype

**Dernière Lueur** is a 3D contemplative prototype developed with Unreal Engine 4.26.2.

The player guides a small living lamp through a dystopian junkyard, solving environmental puzzles by manipulating light and colors via lens switching.  
The game emphasizes **atmosphere**, **exploration**, and **puzzle-solving** based on **light interactions**.

Originally conceptualized as part of the **MAJIC master's degree** (Université Côte d'Azur), *Dernière Lueur* was presented at the **2022 Cannes International Games Festival (FIJ)** and received excellent feedback from the public.

---

## 🎮 Key Features

- ✅ Third-person 3D exploration in a dystopian environment
- ✅ Light and color-based puzzle mechanics via lens switching
- ✅ Bonus interactions hidden throughout the environment
- ✅ Contemplative atmosphere and environmental storytelling
- ✅ Modular gameplay structure using Unreal Engine Blueprints and C++
- ✅ Fully playable vertical slice showcased at a professional event

---

## 🧱 Technologies Used

| Component               | Description                                         |
|--------------------------|-----------------------------------------------------|
| 🕹️ Unreal Engine 4.26.2 | Core engine, level design, scripting                |
| 💻 C++ / Blueprints       | Character control, camera behavior, gameplay logic, puzzles, interactions |
| 🎨 Adobe Suite           | 2D/3D art, texture work                             |
| 🧩 3DS Max / Maya         | 3D modeling and environment creation               |
| 🎧 Wwise                 | Dynamic sound design and event-driven audio         |
| 🎶 Cubase                | Original soundtrack production                     |
| 🖌️ Substance Painter    | Advanced texturing and material creation           |

---

## 👥 Development Team

### Original Concept
- **Théo Benazet**
- **Clémence Gillet**
- **Léo Riba**
- **Benoît Rivière**

### Production
- **Product Owners**: Clémence Gillet, Léo Riba
- **Scrum Master**: Yann Greiveldinger

### Development
- **Lead Developer**: Anthony Hurez
- **Developer**: Jean Deck

### Art Direction
- **Art Director**: Théo Benazet
- **Assistant Art Director**: Léo Riba

### Art & Visual Assets
- **Concept Artist**: Théo Benazet
- **3D Artists**: Théo Benazet, Mélanie Gallardo
- **2D Artists**: Théo Benazet, Jorick Regottaz, Léo Riba

### Game & Level Design
- **Game & Level Designers**: Tristan Charial, Yann Greiveldinger, Jorick Regottaz

### Narrative Design
- **Narrative Designers**: Alexandre Ben Soussan, Clémence Gillet, Joan Iaria

### Sound & Music
- **Sound Designer / Composer**: Léo Riba

### Additional Contributions
- **3D Art Support**: Louis Leclair, Jorick Regottaz, Léo Riba, Benoît Rivière
- **2D Art Support**: Jeremy Thouement
- **Sound Design Support**: Joan Iaria, Jorick Regottaz

### Special Thanks
- **Legal Counsel**: Alix Chuvin, Raphaël Pittet

---

## 🔗 LinkedIn Profiles

- [Théo Benazet](https://www.linkedin.com/in/th%C3%A9o-benazet-a13518203/)
- [Alix Chuvin](https://www.linkedin.com/in/alix-chuvin-b804bb208/)
- [Clémence Gillet](https://www.linkedin.com/in/clemence-gillet-video-game/)
- [Jean Deck](https://www.linkedin.com/in/jean-deck-2b915aa9/)
- [Mélanie Gallardo](https://www.linkedin.com/in/m%C3%A9lanie-gallardo/)
- [Yann Greiveldinger](https://www.linkedin.com/in/yann-greiveldinger-942b34244/)
- [Joan Iaria](https://www.linkedin.com/in/joan-iaria/)
- [Louis Leclair](https://www.linkedin.com/in/louis-leclair-4a0313115/)
- [Jorick Regottaz](https://www.linkedin.com/in/jorick-regottaz/)
- [Léo Riba](https://www.linkedin.com/in/léo-riba-352090165/)
- [Benoît Rivière](https://www.linkedin.com/in/rivi%C3%A8rebeno%C3%AEt/)

> (Other contributors do not have a LinkedIn profile available.)

---

## 📦 Final Build

- Platform: Windows x86_64
- Download: Available in the [Releases section](https://github.com/Kisahn/DerniereLueur/releases)
- Controls:
  - ZQSD to move
  - Space to jump
  - E to interact
  - Mouse Wheel to adjust beam intensity
  - 1 key to equip Yellow Lens
  - 2 key to equip Blue Lens
  - 3 key to equip Orange Lens
  - Escape to pause

Notes:
- The game text is fully in **French**.  
- No English version is available. However, the gameplay remains accessible thanks to strong visual clues.
- AZERTY keyboard required (no remapping possible).
- The downloadable release (v1.1) includes visual improvements made for public showcasing at FIJ 2022.
- The source code available corresponds to version 1.0 (pre-show version).
- Requires Unreal Engine 4.26.2 to rebuild if running from source.

---

## 📥 Repository Requirements

This project uses **Git Large File Storage (Git LFS)** for managing heavy assets (audio files, 3D models, textures).

Before cloning or pulling the repository, make sure Git LFS is installed on your machine:

1. Install Git LFS:  
   https://git-lfs.github.com/

2. Initialize Git LFS on your system (only once):  
   git lfs install

3. Clone the repository normally:  
   git clone https://github.com/Kisahn/DerniereLueur.git

4. Pull the LFS files:  
   cd DerniereLueur  
   git lfs pull

> ⚠️ Note: Without Git LFS, some project files (such as audio, 3D models, and textures) will be missing or corrupted.

---

## 🧪 Learning Objectives

- Build a contemplative 3D exploration prototype with Unreal Engine
- Implement modular gameplay and light/color-based puzzles using Blueprints and C++
- Integrate dynamic and event-driven audio using Wwise middleware
- Conduct production using Agile methods (Scrum framework: PO + SM)
- Showcase a vertical slice at a professional gaming festival (FIJ 2022)
- Design hidden environmental storytelling elements

---

## 🔍 Full Walkthrough

A complete step-by-step solution of the game is available here:  
👉 [Read the full walkthrough 📜](./SOLUTION.md)

---

## 📜 License

This project is released under the [CC BY-NC 4.0 License](https://creativecommons.org/licenses/by-nc/4.0/).  
See the [`LICENSE`](./LICENSE) file for full terms.

> ⚠️ Audio, visual, and animation assets are **not reusable** without explicit permission.
