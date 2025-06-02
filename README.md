# Zombi - Unreal Engine 5 Zombie Survival Game

A Call of Duty Zombies-inspired survival game built in Unreal Engine 5.

## Overview

Zombi is a first-person survival shooter that takes inspiration from the classic Call of Duty Zombies game mode. Fight against waves of undead enemies using an arsenal of weapons while trying to survive as long as possible.

## Features

- **First-Person Shooter Gameplay**: Intense zombie combat with smooth FPS controls
- **Wave-Based Survival**: Face increasingly difficult waves of zombies
- **Weapon Arsenal**: Multiple firearms from the FPS Weapon Bundle
- **AI-Driven Enemies**: Smart zombie AI with custom behavior trees and blackboards
- **Custom Animations**: Unique animation sets for both soldiers and zombies
- **Visual Effects**: Immersive particle effects and materials
- **Interactive UI**: Custom widget-based user interface

## Project Structure

```
Zombi.uproject              # Main Unreal Engine project file
Config/                     # Engine and game configuration files
├── DefaultEditor.ini       # Editor preferences
├── DefaultEngine.ini       # Engine settings
├── DefaultGame.ini         # Game-specific settings
└── DefaultInput.ini        # Input mappings and controls
Content/
├── AI/                     # AI behavior trees and blackboards
│   └── BB_Blackboard.uasset # Main AI blackboard
├── ANIMATIONS/             # Character animation assets
│   ├── Soldier/           # Player character animations
│   └── Zombi/             # Zombie character animations
├── BLUEPRINTS/            # Game logic blueprints
├── CHARACTERS/            # Character assets and blueprints
├── FPS_Weapon_Bundle/     # Weapon assets and systems
├── FX/                    # Visual effects and particles
├── GUNS/                  # Weapon-specific assets
├── Input/                 # Input mapping and controls
├── LEVELS/                # Game maps and levels
├── MATERIALS/             # Custom materials and shaders
├── Megascans/             # Quixel Megascans assets
├── MSPresets/             # Megascans presets
├── PREMADE/               # Pre-built assets and templates
└── WIDGET/                # UI elements and menus
Intermediate/               # Build cache and temporary files
Saved/                      # Save data, logs, and crashes
├── Autosaves/             # Automatic save backups
├── Config/                # User configuration overrides
├── Crashes/               # Crash reports and logs
└── Logs/                  # Runtime and editor logs
```

## Requirements

- **Unreal Engine 5**: Latest stable version
- **Platform**: Windows (primary development platform)
- **Hardware**: 
  - DirectX 12 compatible graphics card
  - 8GB+ RAM recommended
  - 10GB+ available storage

## Getting Started

1. **Clone/Download** the project files
2. **Open** `Zombi.uproject` with Unreal Engine 5
3. **Build** the project when prompted
4. **Play** in the editor or package for your target platform

## Configuration

The game's settings can be modified through the configuration files in the `Config` directory:

- DefaultEngine.ini - Engine settings
- DefaultGame.ini - Game-specific settings  
- DefaultInput.ini - Input mappings and controls
- DefaultEditor.ini - Editor preferences

## Development

This project uses:
- **Blueprint Visual Scripting** for game logic
- **AI Behavior Trees** for zombie intelligence (see BB_Blackboard.uasset)
- **Custom Materials** for visual fidelity
- **Widget Blueprints** for UI systems
- **Megascans Assets** for high-quality environments
- **Third-Person/First-Person** hybrid systems

## Troubleshooting

If you encounter crashes or issues:
1. Check the `Saved/Logs` directory for error logs
2. Crash reports are stored in `Saved/Crashes`
3. Clear the `Intermediate` folder and regenerate project files if needed
4. Auto-saves are available in `Saved/Autosaves` for recovery

## Assets

This project includes:
- **FPS Weapon Bundle**: Professional weapon assets and systems
- **Quixel Megascans**: High-quality photogrammetric materials and models
- **Custom Animations**: Tailored for both soldier and zombie characters
- **AI Systems**: Behavior trees and blackboards for intelligent enemy behavior

## License

This project is for educational/portfolio purposes. Third-party assets (FPS Weapon Bundle, Megascans) retain their respective licenses.

---

*Built with Unreal Engine 5 - A tribute to the classic Call of Duty Zombies experience*
