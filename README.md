# Rise Guys

A fun and challenging 3D obstacle course runner game inspired by popular multiplayer party games. Navigate through various obstacles, avoid hazards, and race to the finish line!

## 🎮 Game Overview

Rise Guys is a physics-based obstacle course game where players control a character running through challenging levels filled with moving obstacles, rotating platforms, and various hazards. The game features ragdoll physics for entertaining character interactions and smooth mobile-optimized controls.

## ✨ Features

- **10 Unique Levels**: Progress through increasingly challenging obstacle courses (Scene01 - Scene10)
- **Intuitive Controls**: Mouse/touch-based swipe controls for horizontal movement
- **Physics-Based Gameplay**: Realistic ragdoll physics for dynamic character interactions
- **Mobile Optimized**: Touch controls designed for mobile platforms
- **Smooth Performance**: Target framerate of 60 FPS for optimal gameplay experience
- **Game Management**: Pause menu, level progression, and restart functionality

## 🕹️ Controls

### PC
- **Mouse Click & Drag**: Hold left mouse button and drag left/right to move the character horizontally
- The character automatically moves forward through the course

### Mobile
- **Touch & Swipe**: Tap and swipe left/right to control horizontal movement
- Automatic forward movement

## 🎯 Gameplay Mechanics

- **Auto-Forward Movement**: Your character automatically runs forward at a constant speed
- **Horizontal Navigation**: Swipe left or right to dodge obstacles and navigate the course
- **Boundary Limits**: The play area is bounded (±9.8 units) to keep players on the track
- **Obstacle Interaction**: Dynamic moving obstacles and rotating platforms challenge your timing
- **Ragdoll Physics**: Character physics activate upon collision for realistic reactions

## 🛠️ Technical Details

### Built With
- **Unity Engine**: Game development platform
- **C# Scripting**: Game logic and mechanics
- **Standard Assets**: Cross-platform input system
- **Physics System**: Unity's built-in physics for realistic interactions

### Key Scripts
- `GameManager.cs`: Handles scene management, pause functionality, and game flow
- `PlayerController.cs`: Controls character movement and input handling
- `CharacterMovement.cs`: Manages character speed and direction
- `MovingObstacle.cs`: Controls dynamic obstacle behavior
- `RagDollEnabler.cs`: Manages ragdoll physics activation
- `PlayerCollision.cs`: Handles collision detection and responses

### Performance
- Target framerate: 60 FPS
- Optimized for mobile devices
- Efficient physics calculations

## 📁 Project Structure

```
Rise-Guys/
├── Assets/
│   ├── Animations/        # Character and object animations
│   ├── Characters/        # 3D character models (.fbx)
│   ├── Materials/         # Textures and materials
│   ├── Music/            # Background music and sound effects
│   ├── Prefabs/          # Reusable game objects
│   ├── Scenes/           # Game levels (Menu + 10 playable scenes)
│   ├── Scripts/          # C# game logic
│   └── Standard Assets/  # Unity standard assets for input
└── README.md
```

## 🚀 Getting Started

### Prerequisites
- Unity 2019.4 LTS or higher
- Windows, macOS, or Linux
- Android SDK (for mobile builds)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Automatic1111/Rise-Guys.git
```

2. Open the project in Unity:
   - Launch Unity Hub
   - Click "Add" and select the project folder
   - Open the project with a compatible Unity version

3. Open the Menu scene:
   - Navigate to `Assets/Scenes/Menu.unity`
   - Press Play to test the game

### Building for Mobile

1. Go to **File > Build Settings**
2. Select **Android** or **iOS** platform
3. Click **Switch Platform**
4. Configure player settings as needed
5. Click **Build** to generate the application

## 🎨 Assets

The game includes:
- Custom 3D character models
- Various obstacle prefabs
- UI elements and menus
- Background music and sound effects
- Multiple font packs for UI

## 🎮 Game Flow

1. **Main Menu**: Start screen with play and quit options
2. **Level Progression**: 10 sequential levels with increasing difficulty
3. **Pause Menu**: Accessible during gameplay
4. **Level Complete**: Advance to the next level
5. **Retry System**: Restart from the current level on failure

## 📝 Development Notes

- The game uses Unity's cross-platform input system for controller support
- Swipe detection threshold is set to 100 pixels for responsive controls
- Boundary collision prevention ensures players stay within the playable area
- Time.timeScale is used for pause functionality

## 🤝 Contributing

Contributions are welcome! If you'd like to improve the game:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is available for educational and personal use.

## 👤 Author

**Cihanser Caliskan**

## 🙏 Acknowledgments

- Unity Technologies for the game engine
- Standard Assets contributors
- Font pack creators (Hammerhead, Square Deal)
- The Fall Guys community for inspiration

---

**Have fun and good luck navigating the obstacles!** 🎉
