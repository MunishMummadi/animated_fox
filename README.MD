# Animated Fox

## Features

- 3D scene with an animated fox model
- Dynamic lighting and shadows
- Camera positioning
- Animation playback controls
- Multiple animation clips
- Utilizes Bevy 0.14.1's animation syste

## Controls

- **Spacebar**: Play / Pause animation
- **Arrow Up / Down**: Speed up / Slow down animation playback
- **Arrow Left / Right**: Seek backward / forward in the animation
- **Digits 1 / 3 / 5**: Play the animation 1, 3, or 5 times respectively
- **L**: Loop the animation indefinitely
- **Enter**: Change to the next animation clip

## Setup

1. Ensure you have Rust and Cargo installed on your system. If not, install them from [https://www.rust-lang.org/](https://www.rust-lang.org/).
2. Clone this repository:
```bash
git clone https://github.com/MunishMummadi/animated_fox.git
cd animated_fox
```
## Prerequisites

- Rust (latest stable version)
- Bevy 0.14.1

## Troubleshooting

If you encounter any issues:
- Verify that your Bevy version is exactly 0.14.1.
- Ensure that the `Fox.glb` file is correctly placed in the assets directory.
- Check that your `Fox.glb` file contains the expected animations.
