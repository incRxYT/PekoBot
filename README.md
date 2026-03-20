# pekoBot

A Geometry Dash botting tool for GD 2.2081, built on top of xdBot by Zilko & Camellia. Designed for macro recording, playback, and level showcases.

---

## Features

- Basic ClickBot
- Practice Fixes
- Seed Modifier
- Noclip
- Show Trajectory
- Layout Mode
- Speedhack
- TPS Bypass
- Frame Stepper
- Safe Mode
- Renderer (with FFmpeg support)
- Instant Respawn
- No Respawn Flash
- No Death Effect
- Macro Saving and Loading
- Macro Auto-Saving

---

## Requirements

- Geometry Dash 2.2081 (Windows)
- [Geode Mod Loader](https://geode-sdk.org/) 5.0.0 or higher
- [geode.custom-keybinds](https://geode-sdk.org/mods/geode.custom-keybinds) v2.0.0 or higher
- FFmpeg (optional, required for the renderer)

---

## Installation

1. Download the latest `adrian.pekobot.geode` from [Releases](../../releases).
2. Open Geometry Dash and navigate to the Geode menu.
3. Go to the Mods tab and click "Install from file".
4. Select the downloaded `.geode` file.
5. Restart Geometry Dash when prompted.

---

## How to Use

1. Open the pekoBot menu using the assigned keybind or the button in the pause menu.
2. Enable the **Record** toggle to start recording your inputs.
3. Complete a practice run of the level.
4. Enable the **Play** toggle and enter the level to replay your macro.

---

## Settings

| Setting | Description |
|---|---|
| Accuracy | Choose between Vanilla, Input Fixes, or Frame Fixes |
| Frame Offset | Offset applied when recording or playing macros |
| TPS Bypass | Override the game's ticks per second |
| Speedhack | Adjust game speed multiplier |
| Frame Fixes Limit | Cap the number of frame fixes per second |
| Lock Delta | Locks the game's delta value |
| Auto Stop Playing | Stops macro playback when it ends |
| Auto Disable Speedhack | Resets speedhack when exiting a level |
| Menu Background Color | Default: #7b68ee |

### Renderer Settings (NakoMod)

| Setting | Description |
|---|---|
| Fast PBO Frame Capture | Async GPU frame reads to prevent freezes |
| Multithreaded Render Queue | Offloads frame processing to a background thread |
| Hardware Acceleration | Choose CPU, NVIDIA (NVENC), AMD (AMF), or Intel (QSV) |
| Aggressive Presets (CPU) | Uses FFmpeg ultrafast preset for faster CPU renders |
| Fast C++ VFlip | Flips frames in code instead of using FFmpeg filters |

---

## Macro Formats

Supports `.gdr` and xdBot's native format. Compatible with macros from Pathfinder and Eclipse.

---

## Building from Source

This mod is based on [xdBot](https://github.com/ZiLko/xdBot). To build from source, follow the Geode SDK setup guide at [docs.geode-sdk.org](https://docs.geode-sdk.org).

---

## Credits

- [Zilko](https://github.com/ZiLko) — original xdBot source
- Camellia — original xdBot development
- Viper — Safe Mode implementation
- ReplayBot — open source renderer code
- [niczwerg105-web](https://github.com/niczwerg105-web) — code contributions

---

## License

This project is a fork of xdBot. Refer to the original repository for license details: [github.com/ZiLko/xdBot](https://github.com/ZiLko/xdBot)
