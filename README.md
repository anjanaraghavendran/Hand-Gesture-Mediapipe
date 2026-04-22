# HandConnect

An advanced web-based augmented reality application that uses hand tracking to create interactive neon visual effects and immersive audio experiences.

## Features

- Real-time hand tracking with MediaPipe Hands
- Multiple visual themes (Rainbow, Cyberpunk, Lava, Ocean, Galaxy)
- Interactive gestures (pinch detection, hand spread recognition)
- Dynamic audio synthesis based on hand movements
- Particle effects, shockwaves, and matrix rain background
- Cross-hand interactions with lightning effects and mandala patterns

## Tech Stack

- **HTML5**: Structure and layout
- **CSS3**: Styling with glassmorphism effects, CSS variables, and backdrop filters
- **JavaScript (ES6+)**: Core logic, event handling, and effects
- **MediaPipe Hands**: Hand detection and landmark tracking
- **Web Audio API**: Real-time audio synthesis and effects
- **Canvas API**: 2D rendering for visual effects
- **WebRTC Camera API**: Camera access for video input

## Usage

1. Open `index.html` in a modern web browser (Chrome, Firefox, Safari, Edge)
2. Grant camera permissions when prompted
3. Click "Enter Experience" to start
4. Use hand gestures in front of the camera to interact with the AR effects
5. Switch between themes using the bottom controls

## Requirements

- Modern browser with WebRTC support
- Camera access (HTTPS required for production, localhost works for development)
- Web Audio API support

## Browser Compatibility

Works best in:
- Chrome 88+
- Firefox 85+
- Safari 14+
- Edge 88+

## License

This project is for educational and demonstration purposes.
