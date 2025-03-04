# Crystal-Chaser

**Authors**: BaKeMoN0

**Date**: 30/06/2024

**Engine & Version**: [Unreal Engine 5.5]

## Introduction
**Welcome to the Crystal Chaser project !**

This document provides an overview of the game concept, along with current and planned features.

<i>Crystal Chaser was developed entirely using Unreal Engine Blueprints, as it is my first project on the engine. This approach allowed for rapid prototyping and a better understanding of Unreal’s workflow. Future improvements may include optimizations or a partial rewrite in C++.</i>

## Concept
Crystal Chaser is an arcade-style game where you control a character that moves horizontally across the screen. When reaching the left or right edge, the character seamlessly teleports to the opposite side, creating a continuous movement loop.

Crystals fall from the top of the screen at varying speeds, and your objective is to catch them before they hit the ground. Each crystal collected earns you points. Additionally, special objects will occasionally drop, granting bonuses or penalties that affect gameplay.

As the game progresses, the speed and frequency of falling objects increase, testing your reflexes and precision in an ever-intensifying challenge.

## Current Features

1. **Player Control :**
   - Move the player left and right using arrow ZQSD keys.

2. **Falling Crystals :**
   - Crystals fall randomly from the top of the screen.

3. **Special Objects :**
   - Stalactites have been added as falling obstacles. If they hit the player or fall nearby, they cause them to fall, resulting in a time loss.

4. **Map :**
   - The game is set in a cave, designed using rock assets to create a natural and immersive environment.
   - A lake has been added using the Water plugin to enhance the scenery in the cave.
   - Niagara effects create a mesmerizing glow of blue fireflies, adding to the cave's atmosphere.

5. **Scoring :**
   - Players earn points for each crystal successfully caught.
   - A rarity system has been implemented, featuring four types of crystals: blue, red, green, and white.
   - Each crystal has a different spawn probability, with rarer crystals granting higher point values.
   - The current score is displayed in the top-left corner of the screen.
   - When a crystal is caught, the points gained appears at the collision point between the player and the crystal.

6. **Round System :**
   - The game is divided into rounds, with each new round increasing the number of falling crystals.
   - The current round number is displayed in the top-left corner alongside the score.

7. **Sound Effects & Music :**
   - Sound effects for key actions, such as catching objects.
   - Background music for an immersive experience.

8. **Game Over Screen :**
   - Display the final score and provide an option to restart the game.

9. **Simple User Interface :**
   - A main menu with game start options.
  
   
