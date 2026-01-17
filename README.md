# Squativa

> Rhythm-based squat game using computer vision • Built at Intania Hackathon

**TL;DR:** Guitar Hero but squat. Camera tracks your form. Compete with friends. Get fit.

## Video Demo

<div align="center">

https://github.com/user-attachments/assets/c9fa4bf5-2ad9-4267-9ed3-0ef721facdf3

</div>

## The Product

<div align="center">
  <img src="https://github.com/user-attachments/assets/fb535a4d-02a8-4955-aa34-877c6f4c1bae" width="49%" />
  <img src="https://github.com/user-attachments/assets/43f24576-8a32-41ba-a8fc-f75eaff639f1" width="49%" />
</div>

## Gameplay

<div align="center">
  <img src="https://github.com/user-attachments/assets/29ad152d-4176-4e43-84c8-9a2c89fed4a7" width="49%" />
  <img src="https://github.com/user-attachments/assets/0616e05b-efd6-4169-8d94-6b8ed67d0c47" width="49%" />
</div>


## What It Does

- ✅ Real-time squat detection via MediaPipe pose estimation
- ✅ Rhythm-based scoring system synced to music
- ✅ 2-player competitive mode
- ✅ Form validation and feedback
- ✅ Multiple songs + difficulty levels

## Tech Stack

```
Python 3.10  |  Pygame  |  OpenCV  |  MediaPipe
```

## Quick Start

```bash
# Clone
git clone https://github.com/Toodmuk/squativa.git
cd squativa

# Install
pip install pygame opencv-python mediapipe

# Run
python main.py
```

That's it. No cap.

## How It Works

```
┌─────────────┐      ┌──────────────┐      ┌─────────────┐
│  Webcam     │─────▶│  MediaPipe   │─────▶│  Game Logic │
│  Feed       │      │  Pose Est.   │      │  & Scoring  │
└─────────────┘      └──────────────┘      └─────────────┘
```

| File | Purpose |
|------|---------|
| `main.py` | Entry point |
| `game.py` | Core game loop + logic |
| `screens.py` | UI screens (menu, game, results) |
| `opcv/squat_late.py` | CV squat detection |
| `utils.py` | Asset loading + rendering |

---

Built with 🔥 at Intania Hackathon
