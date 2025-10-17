# synth-pad-instrument

## Summary

Create 'Synth Pad' - a playable grid-based musical instrument where each pad plays a note and lights up.

🎹 CONCEPT:
A 4x4 or 5x5 grid of colorful pads. Click a pad → it plays a musical note, glows, and animates. It's like a launchpad or drum machine you can actually play melodies on.

✨ THE GRID:
- 16-25 large, tactile pads arranged in a grid
- Each pad is a different vibrant color (neon aesthetic)
- Each pad plays a different note (chromatic or pentatonic scale)
- Pads glow bright when pressed
- Ripple/pulse animation on click
- Shows note name when hovered (C4, D4, E4, etc.)

🎵 SOUND:
- Use Web Audio API
- Clean synth sounds (sine, square, or sawtooth waves)
- Each pad = different pitch
- Notes sustain briefly then fade
- Can play multiple pads simultaneously (chords!)
- Optional: add reverb/echo effect

🎮 INTERACTION:
- Click pad: plays note + animation
- Keyboard support: QWERTY keys mapped to pads (Q=top-left, etc.)
- Can 'play' melodies by clicking in sequence
- Shows visual feedback: which pad was last pressed
- Optional: record and playback feature

🎨 VISUAL STYLE:
- Dark background (black or deep purple)
- Neon-colored pads with gradients
- Glow effects when active
- Modern, musical instrument aesthetic
- Smooth animations
- Large, touch-friendly pads

💫 FEATURES:
- Top controls: 
  * Octave shift buttons (up/down)
  * Volume slider
  * Waveform selector (sine/square/saw)
- Shows currently playing notes
- Optional: metronome visual
- Optional: display played sequence

🎯 THE EXPERIENCE:
Someone clicks a pad → 'beep' + glow. Clicks another → different note. They realize they can play tunes. Start clicking out melodies. Discover keyboard shortcuts. Play chords. Show friends. Actually musical and fun!

It's not just eye candy - it's a playable instrument!

## Features

This application was automatically generated to meet the following requirements:

- Grid of 16-25 clickable pads
- Each pad plays different note
- Web Audio API for sound generation
- Pads glow/animate when clicked
- Keyboard mapping for pads
- Dark background with neon pads
- Volume control
- Octave shift buttons
- Shows note names on hover
- Multiple pads can play simultaneously
- Smooth animations
- Bootstrap 5 for controls
- Responsive layout

## Setup

This is a static web application that requires no build process.

### Local Development

1. Clone this repository
2. Open `index.html` in a web browser
3. Or serve with a local server:
   ```bash
   python -m http.server 8000
   ```


## Usage

Simply open the `index.html` file in a modern web browser. The application includes:
- Bootstrap 5 for responsive design
- Inline JavaScript for functionality
- Embedded data for attachments

## Code Explanation

### HTML Structure
- Uses semantic HTML5 elements
- Bootstrap components for UI
- Responsive design that works on all devices

### JavaScript Functionality
- Handles user interactions
- Processes data from attachments
- Updates DOM elements dynamically
- Includes error handling

### Styling
- Bootstrap 5 framework
- Custom CSS for specific requirements
- Mobile-first responsive design

## Deployment

This application is deployed on GitHub Pages and accessible at the URL provided in the repository settings.

## License

MIT License - See LICENSE file for details

## Auto-Generated

This application was automatically generated using AI-powered code generation.
Generated on: synth-pad-instrument
