# ATLAS-302 

ATLAS-302 is a VR-controlled humanoid robot with two arms and two legs, capable of lifting objects heavier than its own weight over a 302 mm range. The robot streams real-time video to a VR headset for immersive control and interaction.

## 🚀 Features
- Humanoid design: 2 arms, 2 legs
- Arm lift range: 302 mm
- Lifts objects heavier than robot itself
- VR headset first-person control
- Real-time video streaming from head camera
- Emergency stop and software load limits
- Modular 3D-printable design

## 🧠 Project Goals
- Learn humanoid robotics and mechanical design
- Explore VR-based robot control
- Build a safe and functional humanoid robot
- Open-source and reproducible design

## 🛠️ System Overview
- **Control:** VR headset + hand controllers
- **Compute:** Raspberry Pi or similar
- **Motion:** Geared motors / linear actuators for arms
- **Structure:** 3D-printed frame + lightweight materials
- **Lift Mechanism:** Scissor lift or geared arm
- **Legs:** Static or support structure in Stage 1

## 📦 Build Stages
1. Base & stable legs
2. Arm mechanism with 302 mm lift
3. Head camera & VR streaming
4. VR hand control integration
5. Safety systems (software & emergency stop)
6. Optional: leg actuation and walking

## ⚠️ Safety
- Emergency stop button
- Weight limits for arms
- Stable support for humanoid structure


  # Bill of Materials (BOM)

| Item | Quantity | Notes |
|------|----------|-------|
| Micro servo SG90 | 10 | For limbs and joints |
| Raspberry Pi | 1 | Robot brain |
| Pi Camera | 1 | For VR view |
| 3D filament | 1 kg | PLA or PETG |
| PCA9685 Servo Driver | 1 | Controls many servos |
| Lithium battery pack | 1 | 7.4–11.1 V |
| Screws, brackets | As needed | For assembly |


