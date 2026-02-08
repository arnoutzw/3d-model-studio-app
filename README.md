# 3D Model Viewer

A powerful web-based 3D model viewer for STL and 3MF files with advanced visualization capabilities.

## Features

- **File Support**: Load and visualize STL and 3MF files via drag-and-drop or file picker
- **Interactive Controls**: Rotate, zoom, and pan with intuitive mouse and keyboard controls
- **Visualization Options**:
  - Toggle grid, axes, and wireframe modes
  - Auto-rotate functionality for automatic model rotation
  - Flat shading for CAD-like appearance
- **Material Customization**: Adjust color, roughness, and metalness properties
- **Model Information**: View detailed model statistics and properties
- **Camera Controls**:
  - Fit-to-view to auto-frame the entire model
  - Reset view to initial state
- **Performance Metrics**: Real-time FPS counter for performance monitoring
- **Keyboard Shortcuts**:
  - **R** - Reset view
  - **F** - Fit to view
  - **W** - Toggle wireframe
  - **G** - Toggle grid
  - **A** - Toggle axes
  - **S** - Take screenshot
  - **P** - Toggle control panel

## Tech Stack

- **HTML5** - Semantic markup
- **JavaScript** - Core application logic
- **Three.js** - 3D rendering engine
- **Service Worker** - Offline support
- **PWA** - Progressive Web App capabilities

## Getting Started

### Online Demo
Visit the live application: [https://arnoutzw.github.io/3d-model-studio-app/](https://arnoutzw.github.io/3d-model-studio-app/)

### Local Installation
Simply open `index.html` in a modern web browser. No build tools or dependencies required.

### Usage
1. Drag and drop an STL or 3MF file onto the viewer, or use the file picker
2. Use mouse to rotate (left-click + drag), zoom (scroll), and pan (right-click + drag)
3. Use keyboard shortcuts to control visualization options
4. Customize materials and view settings in the control panel

## Browser Support

Requires a modern browser with WebGL support (Chrome, Firefox, Edge, Safari)

## License

MIT License - See LICENSE file for details
