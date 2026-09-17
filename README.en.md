<p align="center">
  <img src="assets/icon.png" width="160" height="160" alt="MoreInfo icon">
</p>

<h1 align="center">MoreInfo</h1>

<p align="center">Keep essential equipment and device status beside the hotbar—no need to repeatedly open your inventory.</p>

<p align="center"><a href="README.md">简体中文</a> · <strong>English</strong></p>

MoreInfo is an in-game information display mod for LeviLauncher on Android. It shows four equipped armor slots to the left of the hotbar, displays FPS and battery temperature to the right, and provides in-game settings that take effect immediately.

## Features

- Shows your helmet, chestplate, leggings, and boots beside the hotbar
- Uses the game's item icons and preserves the enchantment glint
- Displays armor durability bars and hides them by default at full durability
- Long-press an armor slot to view the item's name and exact durability (current / maximum)
- Displays FPS and battery temperature
- Lets you adjust position, scale, and text size
- Switches between vanilla and transparent slot frames
- Saves settings immediately without requiring a game restart

MoreInfo only displays information. It does not automatically swap equipment or modify your inventory.

## Preview

### Equipment and status information beside the hotbar

![Armor slots, FPS, and battery temperature beside the hotbar](assets/screenshots/01-hud-overview.jpg)

### Long-press equipment details and exact durability

![Equipment long-press tooltip](assets/screenshots/02-equipment-tooltip.jpg)

### Equipment bar settings

![Equipment bar settings](assets/screenshots/03-armor-settings.jpg)

### Status information settings

![FPS and battery temperature settings](assets/screenshots/04-status-settings.jpg)

## Supported Versions

- Minecraft 1.26.44.3
- Minecraft 1.26.45.1
- Minecraft 1.26.50.4
- Android ARM64

Install the release that supports your exact Minecraft version. Unlisted versions are rejected instead of being force-loaded, which helps prevent crashes.

## Installation

1. Download the latest `.levipack` from [Releases](https://github.com/188zhuyaqi/MoreInfo/releases).
2. Import the package with LeviLauncher and enable MoreInfo for the target instance.
3. Fully close and restart the game.
4. After entering a world, open **MoreInfo / 装备与状态栏** from the mod menu to customize the display.

If the launcher reports an incompatible version, confirm that your full Minecraft version appears in the supported versions above. Remove any older MoreInfo installation before installing the current release again.

## Notes

- The temperature reading is the device's **battery temperature**, not its CPU or GPU temperature.
- System status data may be briefly delayed or unavailable on some devices.
- When reporting a problem through [Issues](https://github.com/188zhuyaqi/MoreInfo/issues), include the full versions of Minecraft, LeviLauncher, and MoreInfo, along with a screenshot or relevant logs.

Author: **zhuyaqi**

