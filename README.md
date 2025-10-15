# SphereGen - Wireframe Sphere Generator

Interactive 3D wireframe sphere generator with real-time controls and multiple export options.

## 🎯 Features

- **3D Rendering**: Animated wireframe sphere powered by Three.js
- **Real-time Controls**: Modify parameters during execution
- **Multiple Exports**: Save as PNG, standalone HTML, or source code
- **Intuitive Interface**: Complete control panel with sliders

## 🛠️ Available Controls

### Geometry
- **Radius**: 0.5 - 5.0 meters
- **Width Segments**: 8 - 64 (mesh resolution)
- **Height Segments**: 8 - 64 (mesh resolution)

### Rotation
- **Speed X/Y/Z**: -0.05 to 0.05 rad/frame
- **Angle X/Y**: 0 - 360 degrees (initial position)

### Effects
- **Frequency**: 0 - 5 Hz (pulsation rate)
- **Amplitude**: 0 - 0.5 (pulsation intensity)
- **Randomness**: 0 - 1 (unpredictable movement)
- **Flickering**: 0 - 1 (unpredictable flicker)

### Colors
- **Sphere Color**: RGB color picker
- **Background Color**: RGB color picker
- **Invert Colors**: Auto swap sphere/background
- **Opacity**: 0.1 - 1.0 (wireframe transparency)

## 🎮 Buttons

- **▶ PLAY**: Start/resume animation
- **⏸ PAUSE**: Pause animation
- **↻ RESET**: Restore default parameters
- **💾 PNG**: Download current screenshot
- **📄 HTML**: Export standalone HTML
- **👁 CODE**: View and copy source code

## 🚀 Usage

1. Open the HTML file in your browser
2. Adjust parameters using sliders
3. Observe real-time changes
4. Export your creation

## 📋 Technical Details

- **Engine**: Three.js r128
- **Renderer**: WebGL with antialiasing
- **Performance**: 60 FPS on modern browsers
- **Compatibility**: Chrome, Firefox, Safari, Edge

## 🎨 Use Cases

- Visual design prototyping
- Motion graphics references
- 3D animation studies
- Educational demonstrations
- Generative art projects

## 💡 Tips

- Lower segments for retro aesthetic
- High randomness creates organic motion
- Combine oscillation + rotation for complex patterns
- Use opacity < 0.5 for ethereal effects
- Invert colors for instant theme switch

## 📦 Export Options

**PNG**: Static image at current frame
**HTML**: Self-contained file with current settings
**CODE**: Copy/paste ready JavaScript

## 🔧 Requirements

- Modern web browser
- JavaScript enabled
- WebGL support
- Internet connection (for Three.js CDN)

## 📄 License

Free to use for personal and commercial projects.