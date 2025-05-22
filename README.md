HIT137-Assignment3

📁 Project 1: Image Processing Desktop App (Tkinter + OpenCV)

🎯 Description
  A Python desktop application that allows users to load, crop, resize, and save images using a graphical interface. It is built with Tkinter for the GUI and OpenCV for image processing.

✅ Functional Requirements
  1. Image Loading
     a. Select and load images, from the local device
     b. Display the loaded image in the application window
  2. Image Cropping
     a. Draw a rectangle using mouse interaction for image cropping
     b. Provide real-time visual feedback of the selection area while drawing
     c. Display the cropped result alongside the original image
  3. Image Resizing
     a. Slider control for resizing the cropped image
     b. Update the display in real-time as the user moves the slider
  4. Allow saving of the modified image

🔧 Optional Features (if implemented)
  • Implement additional image processing features
  • Add keyboard shortcuts
  • Implement undo/redo functionality



🎮 Project 2: 2D Side-Scrolling Game (Pygame)

🎮 Game Overview
   A side-scrolling 2D game built with Pygame, featuring a player character that can run, jump, and shoot. The game includes multiple levels, enemies, collectibles, scoring, and a boss fight. It demonstrates core object-oriented programming concepts in game development.

✅Functional Requirements

👤 Player Class
  •Move left/right
  •Jump
  •Shoot projectiles
  •Health bar and lives
  •Methods: move(), jump(), shoot(), draw(), take_damage()

💥 Projectile Class
  •Moves in a straight line
  •Deals damage to enemies
  •Methods: update(), draw(), check_collision()

👾 Enemy Class
  •Patrol movement or attack behavior
  •Can take damage and be destroyed
  •Health bar visible
  •Methods: move(), attack(), draw(), take_damage()

🧺 Collectible Class
  •Types: Health boost, Extra life, Score bonus
  •Methods: check_collection(), apply_effect(), draw()

🌍 Level Design
  •Three levels with increasing difficulty
  •Platforms, enemies, and collectibles placed differently per level
  •Boss enemy at the final level

🧮 Scoring System
  •Score increases by:
  •Defeating enemies
  •Collecting items
  •Displayed on screen during gameplay

❤️ Health & Lives
  •Player and enemies have health bars
  •Game ends when lives = 0

🕹️ Game Over Screen
  •Displays score
  •Option to restart the game



💡 Optional: You have three game ideas, select one and implement the above requirements.
  • A game with human-like characters (hero, enemy)
  • A game with an animal (Hero) and human characters (Enemy).
  • A tank-based game navigating through a battlefield to engage with enemy tanks.
