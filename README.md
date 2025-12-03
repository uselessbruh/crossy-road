# 🐸 Crossy Road Deluxe

A browser-based recreation of the classic endless road-crossing game with enhanced 3D-style graphics and smooth animations.

## 🎮 Game Description

Navigate your frog across an endless procedurally-generated world filled with grass fields, busy roads, and flowing rivers. Avoid traffic, ride logs, and don't drown!

## ✨ Features

- **3D-Style Graphics**: Isometric cube rendering with realistic shadows and lighting effects
- **Dynamic Environments**: 
  - Grass fields with varied trees
  - Multi-lane roads with sedans and trucks
  - Rivers with floating logs and animated water effects
- **Smooth Animations**: Jump mechanics, headlight beams, and flowing water
- **Procedural Generation**: Endless gameplay with intelligent lane generation
- **Responsive Controls**: Keyboard arrows or touch/swipe controls for mobile
- **Visual Polish**: Day-night driving effects, shadows, wood grain textures

## 🕹️ How to Play

### Controls
- **Desktop**: Use arrow keys (↑ ↓ ← →) to move
- **Mobile/Tablet**: Swipe in the direction you want to move

### Objective
- Move forward to increase your score
- Avoid cars and trucks on roads
- Jump on logs to cross rivers safely
- Don't fall in the water or get hit by traffic!

### Death Messages
- "Squashed by traffic!" - Hit by a vehicle
- "Glug glug glug..." - Fell in the river
- "Drifted away..." - Floated off-screen on a log

## 🚀 Getting Started

### Installation

1. Clone or download this repository
2. No build process required - pure vanilla JavaScript!

### Running the Game

Simply open `index.html` in any modern web browser:
- Chrome (recommended)
- Firefox
- Safari
- Edge

Or use a local development server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js (http-server)
npx http-server

# Using PHP
php -S localhost:8000
```

Then navigate to `http://localhost:8000`

## 📁 Project Structure

```
crossy/
├── index.html      # Game container and UI screens
├── script.js       # Game logic, graphics engine, and mechanics
├── style.css       # Retro pixel-perfect styling
└── README.md       # This file
```

## 🎨 Technical Highlights

### Graphics Engine
- Custom `Graphics` class with reusable drawing methods
- Shadow rendering with dynamic scaling during jumps
- 3D cube effect using side faces and highlights
- Animated elements (water waves, headlight beams)

### Game Mechanics
- **Lane System**: Modular lane types (grass, road, river) with configurable obstacles
- **Collision Detection**: Precise hitboxes for cars and log platforms
- **Camera System**: Smooth following camera with easing
- **Movement**: Grid-based positioning with smooth interpolation

### Procedural Generation
- Intelligent lane type selection with streak limits
- Dynamic obstacle spawning (trees, cars, logs)
- Balanced difficulty progression

## 🎯 Game Constants

Configurable settings in `CONFIG` object:
- `GRID: 50` - Base grid size for all elements
- `SPEED: 1` - Global speed multiplier
- `MAX_BACK: 6` - Maximum backward movement allowed
- Color schemes for all game elements

## 🖼️ Visual Features

- **Frog Character**: Eyes, legs, body with jumping animation
- **Vehicles**: Two types (sedans and trucks) with directional headlights
- **Environment**: Tree variants, textured logs, animated water
- **UI**: Retro arcade-style menus with pixel font (Press Start 2P)

## 📱 Mobile Support

- Touch-optimized with swipe gestures
- Responsive canvas sizing
- `user-scalable=no` viewport for fixed game area
- Prevented default scrolling behavior

## 🎵 Future Enhancements

Potential additions:
- Sound effects and background music
- Character selection
- Power-ups and collectibles
- Leaderboard/high score persistence
- Additional biomes (desert, snow, etc.)
- Particle effects

## 🛠️ Technologies Used

- **HTML5 Canvas** - Rendering engine
- **Vanilla JavaScript** - Game logic (ES6+)
- **CSS3** - Styling and animations
- **Google Fonts** - Press Start 2P retro font

## 📄 License

This project is open source and available for educational purposes.

## 🙏 Acknowledgments

Inspired by the original Crossy Road mobile game by Hipster Whale.

---

**Enjoy the game! Try to beat your high score! 🏆**
