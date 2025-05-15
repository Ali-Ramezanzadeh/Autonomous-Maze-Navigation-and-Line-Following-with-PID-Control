# Autonomous Maze Navigation & Line Following with PID

An autonomous e-Puck robot project that explores a maze, detects and follows black lines, and returns to the start point — all using PID control and real-time sensor feedback.

 **GitHub Repo:** [Ali-Ramezanzadeh/Autonomous-Maze-Navigation-and-Line-Following-with-PID-Control](https://github.com/Ali-Ramezanzadeh/Autonomous-Maze-Navigation-and-Line-Following-with-PID-Control)

---

## Project Summary

- **Platform:** Webots 2023b
- **Robot:** e-Puck with:
  - Ground sensors
  - Distance sensors
  - Motor encoders
- **Maze Solving:** Depth-First Search (DFS)
- **Control Strategy:** Discrete PID controller (Tustin/Euler method)

---

## Key Features

- Modular and reusable PID controller class
- Accurate line-following using ground sensor data
- Intelligent path tracking for return-to-start logic
- Real-time flag management for sensor synchronization

---

## Challenges & Solutions

- **Sensor Conflicts:** Resolved race conditions by flag update restructuring  
- **Speed Delays:** Improved real-time performance by optimizing flag write timing  
- **Line Exit Glitches:** Reordered actions to ensure clean state transitions

---

## Improvements

- Enhanced line detection with better calibration and noise filtering  
- Optimized maze traversal using priority-based DFS  
- Clean and maintainable code structure for future extensions

---

## Getting Started

```bash
git clone https://github.com/Ali-Ramezanzadeh/Autonomous-Maze-Navigation-and-Line-Following-with-PID-Control
