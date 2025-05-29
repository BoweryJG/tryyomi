# TryYomi - Enhanced Dental Surgery Simulator

A photorealistic 3D dental implant surgery simulator with Google and Facebook authentication.

## Features

- **Ultra-realistic 3D Models**: Photorealistic teeth and jaw anatomy
- **Three Surgical Methods**: 
  - Freehand (high variance)
  - Static Guided (medium variance)  
  - Yomi Robotic (minimal variance)
- **Beautiful Authentication**: Modal-based Google and Facebook sign-in
- **Real-time Metrics**: Track angular deviation, platform deviation, and depth accuracy
- **Performance Analytics**: Score tracking and results saving

## Setup

1. **Run locally with Python:**
   ```bash
   cd ~/TryYomi
   python3 -m http.server 8000
   ```
   Then open http://localhost:8000

2. **Run with Node.js:**
   ```bash
   npm install -g live-server
   npm run dev
   ```

## Technologies

- **Three.js**: 3D graphics and WebGL rendering
- **Supabase**: Authentication and data storage
- **Vanilla JavaScript**: No framework dependencies
- **CSS3**: Modern styling with glassmorphism effects

## Authentication

The app uses Supabase for authentication with:
- Google OAuth
- Facebook OAuth
- Guest mode (no save functionality)

## Game Controls

- **Mouse**: Move drill/implant
- **Click**: Start/stop placement
- **Scroll**: Adjust depth (coming soon)
- **Drag**: Rotate camera view

## Surgical Methods Comparison

| Method | Angular Deviation | Platform Deviation | User Experience |
|--------|------------------|--------------------|-----------------|
| Freehand | 7.03° | 1.63mm | High shake, drift |
| Static Guided | 3.01° | 1.33mm | Medium shake |
| Yomi Robotic | 1.16° | 0.44mm | Minimal variance |

## File Structure

```
TryYomi/
├── index.html       # Landing page with auth
├── simulation.html  # Main surgery simulator
├── package.json     # Project configuration
└── README.md       # This file
```

## Future Enhancements

- [ ] Haptic feedback simulation
- [ ] Multiplayer competitions
- [ ] VR support
- [ ] More tooth types and procedures
- [ ] Global leaderboard
- [ ] Tutorial mode

## Credits

Built with ❤️ for dental professionals worldwide.