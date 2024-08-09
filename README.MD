```markdown
# Animated Fox

## Features

- 3D scene with an animated fox model
- Dynamic lighting and shadows
- Camera positioning
- Animation playback controls
- Multiple animation clips
- Utilizes Bevy 0.14.1's animation system

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

3. Update your `Cargo.toml` to include the following dependency:
   ```toml
   [dependencies]
   bevy = "0.14.1"
   ```

4. Place your `Fox.glb` file in the `assets` directory of your project. This file should contain the 3D model of a fox with at least three animations.

## Running the Application

To run the application, use the following command in your terminal:

```bash
cargo run
```

## Description

This Rust application creates a 3D environment featuring an animated fox model. The scene includes:

- A ground plane
- Directional lighting with shadows
- A 3D camera
- A fox model with multiple animations

Users can switch between different animations using keyboard inputs.

## Prerequisites

- Rust (latest stable version)
- Bevy 0.14.1

## Notes

- Ensure you're using Bevy 0.14.1 to avoid compatibility issues.
- The code assumes that your `Fox.glb` file contains at least three animations named "Animation0", "Animation1", and "Animation2".

## Troubleshooting

If you encounter any issues:

- Verify that your Bevy version is exactly 0.14.1
- Ensure that the `Fox.glb` file is correctly placed in the `assets` directory
- Check that your `Fox.glb` file contains the expected animations
```