# CuBiC Game

A 3D interactive cube grid game with VR support, built using Three.js.

## Features

- 16 × 16 × 16 grid of colorful cubes
- Interactive cube selection
- First-person view mode
- VR support with controller interaction
- Color-coded cubes based on position
- Smooth orbit controls for camera movement

## How to Run

1. Open `cubic.html` in a modern web browser (Chrome, Firefox, or Edge recommended)
2. Choose between Normal Mode or VR Mode:
   - Normal Mode: Use mouse controls to interact with the cube grid
   - VR Mode: Use VR headset and controllers to interact in virtual reality

## Controls

### Normal Mode
- Click and drag to rotate the view
- Scroll wheel to zoom in/out
- Click on a cube to select it
- Double-click on a cube to enter first-person view
- Use the "Return to Menu" button to go back to the main menu

### VR Mode
- Use VR controllers to point and select cubes
- Physical movement for navigation
- Controller triggers for interaction

## Technical Details

The game is built using:
- Three.js for 3D graphics
- WebXR for VR support
- Pure JavaScript for game logic

## File Structure

```
Moving_These/
├── cubic.html           # Main game file
├── node_modules/        # Dependencies
│   ├── three/          # Three.js library files
│   └── @webxr-input-profiles/  # WebXR controller profiles
└── README.md           # This file
```

## Notes

- VR mode requires a WebXR-compatible browser and VR headset
- The game works best with a dedicated graphics card
- For optimal performance, use the latest version of your web browser 