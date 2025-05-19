# Unity-Autonomous-Car-Navigation
Autonomous robot car in Unity that navigates through checkpoints, adjusts motor torque based on slope and turning angle, and handles wheel physics using WheelColliders.
# Unity Autonomous Car Navigation 🚗🧠

This project simulates an autonomous robot car in Unity that navigates a series of checkpoints using custom logic for steering, motor torque, slope detection, and wheel collider physics.

## 🎯 Features

- ✅ Checkpoint-based navigation
- 🌀 Steering logic with angle constraints
- ⛰️ Slope detection using raycasts from wheels
- ⚙️ Dynamic torque adjustment for turns and inclines
- 🛞 Realistic wheel physics using `WheelColliders`
- 🧩 Modular, readable C# codebase

## 🧠 How It Works

- The car moves towards a sequence of predefined checkpoints.
- It calculates the angle to the next checkpoint and steers accordingly.
- Torque is adjusted dynamically based on:
  - Turning angle
  - Detected slope beneath the wheels
- The robot slows down on sharp turns and applies brake torque when needed.

## 📂 Folder Structure

