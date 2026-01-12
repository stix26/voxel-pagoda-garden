# 🌸 Voxel Pagoda Garden

An interactive 3D voxel-style Japanese garden scene featuring a traditional pagoda, cherry blossom trees, koi pond, and serene landscape. Built with Three.js and pure JavaScript.

![Voxel Pagoda Garden Demo](demo.gif)

## 📖 About

**Voxel Pagoda Garden** (桜庭園 - Sakura Pagoda Garden) is a beautiful, interactive 3D scene that combines the charm of voxel art with traditional Japanese garden aesthetics. The scene features:

- **5-tiered Pagoda** - A detailed traditional Japanese pagoda with red and gold accents
- **Cherry Blossom Trees** - Multiple sakura trees with animated falling petals
- **Koi Pond** - A tranquil pond with animated koi fish swimming in circles
- **Stone Bridge** - An arched bridge spanning the pond
- **Stone Lanterns** - Illuminated lanterns scattered throughout the garden
- **Bamboo Clusters** - Natural bamboo groves adding to the atmosphere
- **Animated Elements** - Falling cherry blossom petals and swimming koi fish

## 🎮 Controls

- **Drag** - Orbit around the scene
- **Scroll** - Zoom in and out
- **Double-click** - Reset camera to default position
- **Touch** - Full touch support for mobile devices

## 🚀 Getting Started

Simply open `voxel-pagoda-garden.html` in a modern web browser. No build process or dependencies required - everything runs client-side using Three.js from a CDN.

### Requirements

- A modern web browser with WebGL support
- Internet connection (for Three.js CDN)

## 🛠️ Technical Details

### Technologies Used

- **Three.js r128** - 3D graphics library
- **Pure JavaScript** - No frameworks, vanilla JS
- **WebGL** - Hardware-accelerated rendering
- **Voxel-based Rendering** - Each element is built from individual voxel cubes

### Features

- **Real-time Shadows** - Soft shadow mapping for realistic lighting
- **Fog Effects** - Atmospheric fog for depth
- **Dynamic Lighting** - Multiple light sources including directional and point lights
- **Particle System** - 100+ falling cherry blossom petals
- **Smooth Camera Controls** - Interpolated camera movement
- **Responsive Design** - Adapts to different screen sizes

### Scene Elements

The scene is procedurally generated and includes:

- Terrain with grass, water, and stone paths
- Pagoda with 5 tiers, stairs, and decorative elements
- Multiple cherry trees with randomized sizes and positions
- Bamboo clusters with natural variation
- Stone lanterns with glowing light sources
- Arch bridge with railings
- Koi fish with circular swimming patterns
- Cherry blossom petal particles

## 🎨 Color Palette

The scene uses a carefully crafted color palette inspired by traditional Japanese aesthetics:

- **Pagoda Red** (`#c41e3a`) - Main pagoda structure
- **Pagoda Gold** (`#ffd700`) - Accent details
- **Cherry Blossom** (`#ffb7c5`) - Sakura petals
- **Bamboo Green** (`#4a7c23`) - Bamboo stalks
- **Water Blue** (`#40e0d0`) - Pond water
- **Stone Gray** (`#808080`) - Stone elements

## 📝 Notes

- The scene includes a loading screen that fades out after initialization
- All animations run at 60fps using `requestAnimationFrame`
- The scene is optimized for performance with efficient voxel rendering
- Mobile-friendly with touch controls

## 📄 License

This project is open source and available for personal and educational use.

## 🙏 Credits

Built with [Three.js](https://threejs.org/) - a JavaScript 3D library.

---

*Experience the tranquility of a traditional Japanese garden in voxel form.*
