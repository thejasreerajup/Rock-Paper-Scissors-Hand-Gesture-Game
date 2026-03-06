# Rock Paper Scissors Game using OpenCV & MediaPipe

This project is an interactive **Rock-Paper-Scissors game** where the player competes against the computer using **hand gestures detected through a webcam**.

The system uses **MediaPipe for hand landmark detection** and **OpenCV for real-time video processing**.

---

## Project Overview

The goal of this project is to create a **real-time gesture recognition game** using computer vision.  
The player shows **rock, paper, or scissors using their hand**, and the system detects the gesture and compares it with the computer's randomly generated move.

The game continues until **either the player or the computer reaches 10 points**, after which the **winner is displayed and the game stops**.



---

## Features

- Real-time hand gesture detection
- Rock / Paper / Scissors recognition
- Countdown timer before each round
- Computer random move generation
- Live score tracking
- Game ends when a player reaches 10 points

---

## Technologies Used

- Python
- OpenCV
- MediaPipe
- NumPy

---

## How the Game Works

1. The webcam captures the player's hand gesture.
2. MediaPipe detects hand landmarks.
3. The gesture is interpreted as:
   - Rock
   - Paper
   - Scissors
4. The computer randomly chooses a move.
5. The winner of the round is calculated.
6. The score updates.
7. The game ends when either the player or computer reaches **10 points**.

---

## Installation

Install the required libraries:

```bash
pip install -r requirements.txt
```

---

##  How to Run the Project

Run the Jupyter Notebook file:

```bash
rps_game.ipynb
```


Make sure your **webcam is enabled**.

---
