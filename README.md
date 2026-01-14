<div align="center">

# 🏯 桜庭園 • Voxel Pagoda Garden

### *A Journey Through Digital Zen*

[![Made with Three.js](https://img.shields.io/badge/Made%20with-Three.js-000000?style=for-the-badge&logo=three.js)](https://threejs.org/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![WebGL](https://img.shields.io/badge/WebGL-990000?style=for-the-badge&logo=webgl&logoColor=white)](https://www.khronos.org/webgl/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](LICENSE)

**An immersive 3D voxel-style Japanese garden experience featuring traditional architecture, animated nature, and serene landscapes.**

[🎮 Try Demo](#-quick-start) • [📖 Documentation](#-features) • [🎨 Gallery](#-gallery) • [🤝 Contributing](#-contributing)

![Voxel Pagoda Garden Demo](demo.gif)

</div>

---

## ✨ What is This?

**Voxel Pagoda Garden** is a WebGL-powered, interactive 3D environment that brings the tranquility of a traditional Japanese garden into your browser. Built entirely with **Three.js** and vanilla JavaScript, this project showcases the beauty of voxel art combined with procedural generation and real-time rendering.

> *"Where traditional aesthetics meet modern web technology"* 🌸

---

## 🎯 Two Versions, One Vision

Choose your experience:

### 🎴 **Classic Version** → `voxel-pagoda-garden.html`
The original voxel garden experience with all core features and animations.

**Perfect for:** First-time visitors, quick demos, performance-focused environments

### 🌟 **Interactive Version** → `voxel-pagoda-garden-interactive.html`
An enhanced experience with dynamic controls and atmospheric features.

**Perfect for:** Exploration, customization, showcasing advanced features

<details>
<summary><b>🔍 View Feature Comparison</b></summary>

| Feature | Classic | Interactive |
|---------|:-------:|:-----------:|
| 5-Tiered Pagoda | ✅ | ✅ |
| Cherry Blossom Trees | ✅ | ✅ |
| Animated Petals (200+) | ✅ | ✅ |
| Koi Pond with Fish | ✅ | ✅ |
| Stone Lanterns | ✅ | ✅ |
| Bamboo Groves | ✅ | ✅ |
| Arched Bridge | ✅ | ✅ |
| Camera Controls | ✅ | ✅ |
| **Auto-Rotate Toggle** | ❌ | ✅ |
| **Petal Visibility Control** | ❌ | ✅ |
| **Time of Day Cycling** | ❌ | ✅ |
| **Enhanced UI Overlay** | ❌ | ✅ |
| **Dark/Light Mode** | ❌ | ✅ |
| **Dynamic Lantern Brightness** | ❌ | ✅ |

</details>

---

## 🚀 Quick Start

**No installation. No build process. No dependencies.**

Just download and open either HTML file in a modern browser:

```bash
# Clone the repository
git clone https://github.com/stix26/voxel-pagoda-garden.git

# Navigate to the directory
cd voxel-pagoda-garden

# Open in your browser (macOS example)
open voxel-pagoda-garden.html
# or
open voxel-pagoda-garden-interactive.html
```

**Or simply:** Download the HTML file and double-click! 🎉

### System Requirements
- ✅ Modern web browser (Chrome, Firefox, Safari, Edge)
- ✅ WebGL support (enabled by default in modern browsers)
- ✅ Internet connection (for Three.js CDN)

---

## 🎮 Controls

<div align="center">

| Action | Input | Description |
|:------:|:------|:------------|
| 🖱️ | **Drag** | Orbit camera around the scene |
| 🔄 | **Scroll** | Zoom in and out |
| 👆 | **Double-Click** | Reset camera to default position |
| 📱 | **Touch** | Full mobile support with gestures |

</div>

### Interactive Version Additional Controls

<div align="center">

| Button | Function |
|:------:|:---------|
| **⟳ Auto Rotate** | Toggle automatic camera rotation |
| **🌸 Petals** | Show/hide falling cherry blossoms |
| **🌅 Time of Day** | Cycle through sunset → night → dawn |

</div>

---

## 🌸 Features

### 🏗️ Architecture & Structures

<table>
<tr>
<td width="50%">

#### 🏯 Five-Tiered Pagoda
- Authentic multi-story design
- Red & gold color scheme
- Curved roof architecture
- Gold spire with ornamental details
- Corner pillars and support beams

</td>
<td width="50%">

#### 🌉 Arched Stone Bridge
- Curved design with railings
- Spans across the koi pond
- Wooden deck construction
- Traditional Japanese aesthetic

</td>
</tr>
<tr>
<td width="50%">

#### 🏮 Stone Lanterns
- Glowing inner chambers
- Dynamic point lighting
- Traditional tōrō design
- Strategically placed throughout garden

</td>
<td width="50%">

#### 🪨 Rock Gardens
- Procedurally placed stones
- Varied sizes and arrangements
- Natural color variations
- Zen garden aesthetic

</td>
</tr>
</table>

### 🌿 Nature & Environment

<table>
<tr>
<td width="50%">

#### 🌸 Cherry Blossom Trees
- 15+ trees with unique variations
- Randomized canopy sizes
- Multiple pink shades
- Organic branching patterns
- 200+ falling animated petals

</td>
<td width="50%">

#### 🎋 Bamboo Groves
- Natural clustering
- Height variations
- Leaf details at top
- Multiple grove locations

</td>
</tr>
<tr>
<td width="50%">

#### 🐟 Koi Pond
- Animated swimming fish (5 colors)
- Tranquil water with reflections
- Lily pads and flowers
- Stone border edging
- Circular fish patterns

</td>
<td width="50%">

#### 🌿 Ground Cover
- Varied grass colors (5 shades)
- Stone walking paths
- Scattered wildflowers
- Grass tufts and details

</td>
</tr>
</table>

### 🎨 Visual & Technical Features

<table>
<tr>
<td width="33%">

**🌅 Lighting System**
- Real-time shadows
- Soft shadow mapping
- Multiple light sources
- Directional sun
- Point lights from lanterns
- Hemisphere lighting
- Dynamic fog effects

</td>
<td width="33%">

**🎬 Animation System**
- 60 FPS animations
- Smooth camera interpolation
- Falling petal physics
- Swimming koi movement
- Auto-rotate camera mode
- Particle system (200+ petals)

</td>
<td width="33%">

**🎨 Rendering**
- Voxel-based architecture
- WebGL acceleration
- Anti-aliasing
- High pixel ratio support
- Procedural generation
- Optimized performance

</td>
</tr>
</table>

### ⚡ Interactive Version Exclusive Features

#### 🌍 **Time of Day System**
Experience three distinct atmospheres with unique lighting, colors, and moods:

| Time | Atmosphere | Sky Color | Lighting | Lantern Brightness |
|:----:|:-----------|:----------|:---------|:-------------------|
| 🌅 **Sunset** | Warm & romantic | Orange-red gradient | Golden hour glow | Moderate |
| 🌙 **Night** | Mysterious & serene | Deep blue-purple | Moonlight | Bright ✨ |
| 🌄 **Dawn** | Fresh & hopeful | Pink-lavender | Soft morning light | Subtle |

#### 🎛️ **Interactive Controls**
- Toggle animations on/off
- Control petal effects
- Customize viewing experience
- Glowing UI with Japanese typography

#### 🎨 **Theme Adaptation**
- Automatically detects system theme
- Custom light mode palette
- Seamless theme switching
- Beautiful gradient backgrounds

---

## 🎨 Gallery

### Color Palette

<div align="center">

| Color | Hex | Usage |
|:------|:----|:------|
| 🏮 **Pagoda Red** | `#c41e3a` | Main pagoda structure |
| ✨ **Pagoda Gold** | `#ffd700` | Accent details & spire |
| 🌸 **Cherry Blossom** | `#ffb7c5` | Sakura petals & flowers |
| 🍃 **Bamboo Green** | `#4a7c23` | Bamboo stalks & leaves |
| 💧 **Water Blue** | `#40e0d0` | Pond water surface |
| 🪨 **Stone Gray** | `#808080` | Stone elements & lanterns |
| 🌾 **Grass Green** | `#228b22` | Ground grass & bushes |
| 🌲 **Wood Brown** | `#8b4513` | Bridge & tree trunks |

</div>

### Scene Statistics

<div align="center">

| Element | Count | Details |
|:--------|:-----:|:--------|
| 🏯 Pagoda Tiers | 5 | Multi-story structure |
| 🌸 Cherry Trees | 15 | Various sizes |
| 🏮 Stone Lanterns | 12 | With point lights |
| 🐟 Koi Fish | 5 | Animated swimming |
| 🎋 Bamboo Stalks | 21 | In 3 clusters |
| 🪨 Rock Formations | 12 | Decorative gardens |
| 🌺 Bushes | 8 | With flowers |
| ❄️ Cherry Petals | 200 | Falling particles |

</div>

---

## 🛠️ Technical Architecture

### Technology Stack

```
┌─────────────────────────────────────────────┐
│           Browser (WebGL Enabled)           │
├─────────────────────────────────────────────┤
│              Three.js r128                  │
│         (3D Rendering Library)              │
├─────────────────────────────────────────────┤
│         Vanilla JavaScript (ES6+)           │
│     (No frameworks, pure JS logic)          │
├─────────────────────────────────────────────┤
│        HTML5 + CSS3 (UI Layer)              │
│     (Responsive design & animations)        │
└─────────────────────────────────────────────┘
```

### Code Structure

```javascript
// Core Components
├── Scene Setup
│   ├── Camera configuration
│   ├── Renderer initialization
│   └── Lighting system
│
├── Voxel Builder
│   └── createVoxel(x, y, z, color, size)
│
├── Structure Generators
│   ├── createPagoda() - 5-tiered temple
│   ├── createCherryTree() - Procedural trees
│   ├── createLantern() - Stone lanterns
│   ├── createPond() - Koi pond with fish
│   ├── createBridge() - Arched bridge
│   ├── createBamboo() - Bamboo clusters
│   ├── createBush() - Flowering bushes
│   └── createGround() - Terrain generation
│
├── Animation Systems
│   ├── updatePetals() - Particle physics
│   ├── Koi fish movement
│   └── Camera auto-rotation
│
└── Control Systems
    ├── Mouse/touch input
    ├── Camera manipulation
    └── Interactive UI (Enhanced version)
```

### Performance Optimizations

- ✅ **Efficient Voxel Rendering**: Shared geometry and materials
- ✅ **Shadow Map Optimization**: 2048x2048 resolution
- ✅ **Particle System**: Instanced petal meshes
- ✅ **LOD Considerations**: Strategic detail levels
- ✅ **Responsive Rendering**: Adaptive pixel ratio
- ✅ **Memory Management**: Object pooling for particles

---

## 📱 Browser Compatibility

<div align="center">

| Browser | Version | Status |
|:--------|:--------|:------:|
| 🔵 **Chrome** | 90+ | ✅ Fully Supported |
| 🦊 **Firefox** | 88+ | ✅ Fully Supported |
| 🧭 **Safari** | 14+ | ✅ Fully Supported |
| 🔷 **Edge** | 90+ | ✅ Fully Supported |
| 📱 **Mobile** | iOS 14+, Android 10+ | ✅ Touch Support |

</div>

---

## 📚 Documentation

### File Structure

```
voxel-pagoda-garden/
├── 📄 voxel-pagoda-garden.html        # Classic version
├── 📄 voxel-pagoda-garden-interactive.html  # Enhanced version
├── 📖 README.md                       # This file
├── 🎬 demo.gif                        # Animated preview
└── 📝 .gitignore                      # Git ignore rules
```

### Key Functions

<details>
<summary><b>Core Functions Reference</b></summary>

#### `createVoxel(x, y, z, color, size)`
Creates a single voxel cube at specified position.

**Parameters:**
- `x`, `y`, `z`: 3D coordinates
- `color`: Hex color value
- `size`: Cube dimensions (default: 1)

**Returns:** Three.js Mesh object

---

#### `createPagoda(baseX, baseZ)`
Generates a complete 5-tiered pagoda structure.

**Features:**
- Multiple floors with decreasing sizes
- Curved roofs with gold trim
- Corner pillars
- Decorative spire

---

#### `createCherryTree(x, z, size)`
Procedurally generates a cherry blossom tree.

**Features:**
- Randomized branching
- Varied canopy sizes
- Multiple pink shades
- Natural variations

---

#### `createPond(centerX, centerZ, radius)`
Creates a koi pond with animated fish.

**Features:**
- Water surface with transparency
- Swimming koi (5 colors)
- Lily pads and flowers
- Stone border

</details>

---

## 🎓 Learning Resources

This project demonstrates:

- 🎨 **3D Graphics Programming** with Three.js
- 🧊 **Voxel-based Rendering** techniques
- 🎬 **Animation Systems** and particle effects
- 🌟 **Lighting & Shadows** in WebGL
- 🎮 **Interactive Camera Controls**
- 📱 **Responsive Web Design**
- ⚡ **Performance Optimization**
- 🎨 **Procedural Generation**

Perfect for:
- Learning Three.js fundamentals
- Understanding voxel art creation
- Studying 3D scene composition
- Exploring procedural generation
- Building interactive web experiences

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

### Ideas for Enhancement
- 🎵 Add ambient sound effects (water, wind, birds)
- 🌦️ Weather system (rain, snow, wind)
- 🌙 Day/night cycle animation
- 🏃 First-person walking mode
- 📸 Screenshot/video capture feature
- 🎨 Customizable color themes
- 🗺️ Minimap navigation
- 🔊 Audio controls

### How to Contribute
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

**You are free to:**
- ✅ Use commercially
- ✅ Modify
- ✅ Distribute
- ✅ Private use

**With attribution:** Please credit the original project!

---

## 🙏 Acknowledgments

### Technologies
- **[Three.js](https://threejs.org/)** - The amazing 3D library that powers this project
- **WebGL** - For hardware-accelerated graphics
- **JavaScript ES6+** - For modern, clean code

### Inspiration
- 🏯 Traditional Japanese garden design
- 🎮 Voxel art and Minecraft aesthetics
- 🎨 Low-poly 3D art movement
- 🌸 Zen philosophy and minimalism

---

## 📧 Contact & Support

<div align="center">

**Found a bug?** [Open an issue](https://github.com/stix26/voxel-pagoda-garden/issues)

**Have a question?** [Start a discussion](https://github.com/stix26/voxel-pagoda-garden/discussions)

**Love the project?** Give it a ⭐ on GitHub!

---

### Share Your Experience

If you enjoyed this project, please consider:
- ⭐ **Starring** the repository
- 🐛 **Reporting** bugs or issues
- 💡 **Suggesting** new features
- 🔀 **Forking** and creating your own version
- 📢 **Sharing** with others

</div>

---

<div align="center">

### 🌸 *Made with ❤️ and JavaScript* 🌸

**Experience the tranquility of a traditional Japanese garden in voxel form.**

[⬆ Back to Top](#-桜庭園--voxel-pagoda-garden)

---

*桜の花は春の詩*  
*Cherry blossoms are the poetry of spring*

</div>
