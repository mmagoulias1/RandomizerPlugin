# McRandomize Plugin

A Minecraft plugin that adds random elements to gameplay, making each session unique and unpredictable.

## Features

- **Random Item Drops**: When breaking blocks, there's a 30% chance to receive a random item
  - Possible items include diamonds, iron ingots, gold ingots, emeralds, coal, redstone, lapis lazuli, quartz, and glowstone dust

- **Random Health/Damage**: When taking damage, the amount is randomized between 0 and 10
  - Creates unpredictable combat scenarios

- **Random Effects**: When taking damage, there's a 40% chance to receive a random potion effect
  - Possible effects include speed, jump boost, invisibility, glowing, levitation, slow falling, confusion, and blindness
  - Effects last between 10 and 30 seconds with random intensity levels

## Installation

1. Download the latest release from the releases page
2. Place the JAR file in your Minecraft server's `plugins` folder
3. Restart your server

## Requirements

- Minecraft 1.20.4
- Spigot/Paper server

## Building from Source

1. Clone the repository
2. Run `./gradlew build`
3. Find the JAR file in `plugin/build/libs/`

## License

This project is licensed under the MIT License - see the LICENSE file for details. 