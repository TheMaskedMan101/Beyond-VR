# Project Systems & Technology Overview

Beyond uses a combination of Unity tools, community-driven systems, and custom-built features to recreate and expand the Sail VR experience. Below is a breakdown of the technologies and assets we use for different aspects of development.

---

## 🌍 Map Modeling & Environment Design

We use multiple Unity Asset Store packs and custom-made assets to produce high-quality, stylized, and performant maps.

**Asset Sources**
- Low Poly 3D Models Pack
- Additional Unity Asset Store environment packs
- Custom mesh work created by the Beyond dev team and contributors

**Map Types**
- **Classic Sail VR maps** (restored & updated)
- **Reworked modern maps** with visual and gameplay improvements
- **Original Beyond maps** uniquely designed for our client

**Features**
- Map selection directly in the **main menu**
- Optimized lighting and assets for both PC and VR
- Community contributions encouraged (map makers, 3D artists welcome)

---

## 🌊 Wave Engine / Water System

For realistic and dynamic ocean behavior, Beyond uses the **Crest Water System**:  
https://github.com/wave-harmonic/crest

**Why Crest?**
- High-performance, VR-friendly ocean rendering  
- Realistic wave simulation and motion  
- Buoyancy for boats, props, and floating objects  
- Configurable ocean presets (calm seas, storms, rough waves)  
- Expandable for future weather and water events  

This system helps restore classic wave mechanics from older Sail VR builds while enabling entirely new water-based gameplay experiments.

---

## ⚙️ Physics & Interaction Systems

Beyond blends Unity’s physics engine with custom modifications:

- VR hand interactions  
- Climbing and movement extensions  
- Object grabbing improvements  
- Experimental modifiers for mods and cheats  
- Physics optimized for both standalone VR and PC

---

## 🎮 VR Integration & Platform Support

Beyond is developed for both VR and non-VR platforms:

- **PC Client (Windows)**
- **Android / Quest APK Builds**

**Included Features**
- Full cross-play between PC and VR
- Unified UI design across platforms
- Custom VR settings for comfort, performance, and accessibility
- Stable controls and HUD tailored for VR input

---

## 🌐 Network & Server Technology

We use a custom backend to support community-driven multiplayer:

- Cross-platform server compatibility
- Custom anti-cheat / ban management
- Player authentication system
- Support for modded lobbies
- Stable multiplayer sessions across different hardware types

This system ensures fair play, community safety, and flexibility for testing or modded environments.

---

## 🎨 Art Pipeline & Asset Workflow

To maintain smooth VR performance, Beyond follows a consistent asset workflow:

- Low-poly, stylized assets for readability in VR  
- Optimized textures, LOD groups, and draw call reduction  
- Shared material library for asset consistency  
- Lighting presets for Quest and PC builds  
- Performance testing and profiling on all platforms  

Contributors are encouraged to follow this pipeline for compatibility.

---

## 🛠️ Development Tools

Beyond developers use the following tools and frameworks:

- **Unity 2022 LTS**
- **Crest Water System**
- **Blender** for modeling and prop creation
- **GitHub** for version control
- **Custom Beyond debugging tools**
- **Internal modding SDK (in development)**

These tools help maintain quality, support collaboration, and ensure consistent development across contributors.

---

