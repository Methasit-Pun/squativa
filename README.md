# Squativa - the Squat Game




https://github.com/user-attachments/assets/c9fa4bf5-2ad9-4267-9ed3-0ef721facdf3

![20250330_135509](https://github.com/user-attachments/assets/29ad152d-4176-4e43-84c8-9a2c89fed4a7)
![20250330_135506](https://github.com/user-attachments/assets/0616e05b-efd6-4169-8d94-6b8ed67d0c47)
![20250329_231821](https://github.com/user-attachments/assets/3b7b956b-d968-41a0-a7e9-4f0333c9a6a2)




Squativa is an interactive fitness game that combines rhythm and squats. Players perform squats in sync with a rhythm pattern while maintaining proper form to score points. The game supports two players and uses a webcam for squat detection.
Presented by Intania Hackathon

## Features
- **Rhythm-Based Gameplay**: Perform squats in sync with the rhythm pattern.
- **Real-Time Feedback**: Detects squat form and provides feedback on posture.
- **Multiplayer Support**: Two players can compete simultaneously.
- **Custom Songs and Difficulties**: Select songs and difficulty levels.
- **Dynamic Graphics**: Visual feedback with squat graphics and target zones.

## Requirements
- Python 3.10
- Pygame
- OpenCV
- MediaPipe

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Toodmuk/squativa.git
   cd squativa
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
   or
      ```bash
   pip install mediapipe
   pip install opencv-python
   pip install pygame
   ```

## Usage
1. Run the game:
   ```bash
   python main.py
   ```
2. Use the menu to select a song and difficulty.
3. Follow the rhythm and perform squats in front of the webcam.

## Folder Structure
- `game.py`: Main game logic.
- `screens.py`: Handles different game screens (menu, countdown, game, results).
- `opcv/squat_late.py`: Squat detection using MediaPipe and OpenCV.
- `utils.py`: Utility functions for loading assets and rendering graphics.

## Controls
- **Menu Navigation**: Use the mouse to select options.
- **Quit**: Press `Q` or `Esc` to exit the game.

## License
This project is for educational purposes only.
