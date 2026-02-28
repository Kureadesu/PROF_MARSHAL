# Prof. Marshal: VR Ground Marshalling Training System

**An immersive virtual reality application for airport ground marshalling education with motion-capture-based assessment**

## 🎯 Overview

Prof. Marshal is a VR training system designed to enhance ground marshalling education through an interactive 3D airport environment. The application features real-time hand signal recognition, animated aircraft feedback, and comprehensive assessment capabilities, providing aviation students with a safe, repeatable training environment that simulates real-world airport ground operations.

## ✨ Key Features

### Training Mode
- Three aircraft types: UH-1H Helicopter, Cessna 150, and Boeing 737
- Two-level progressive learning modules
- Realistic environmental conditions (day/night, rain, snow)
- Immersive airport ground environment

### Practice Mode
- Safe environment for skill refinement
- Real-time hand signal recognition with visual feedback
- Interactive checklist system with color-coded progress
- Immediate aircraft animation responses to correct signals

### Assessment Mode
- Instructor-gated access with 6-digit PIN
- 10-minute timed assessments
- Three-attempt limit per hand signal
- Real-time pose matching against predefined library
- Automated scoring and progress tracking
- Scoreboard system with trainee performance records

### Technical Capabilities
- Motion-capture-based hand signal recognition
- Event-driven C# scripts for real-time error detection
- Visual cues, warnings, and pop-up feedback
- Pose library for standardized signal validation
- Cross-platform XR support via OpenXR

## 🛠️ Technical Stack

- **Engine:** Unity 2021.3.45f1 LTS
- **XR Framework:** XR Interaction Toolkit, OpenXR, VRTK v3
- **Programming:** C# (Visual Studio 2022)
- **3D Modeling:** Blender 4.3 (assets), Blender 4.2 (animations)
- **Hardware:** Meta Quest 2 VR headset and controllers
- **Development Tools:** Meta Developer Hub, Oculus Quest Link
- **UI/UX Design:** Figma

## 📊 System Architecture

- **XR Rig Integration:** Accurate body and hand-movement tracking
- **Pose Recognition:** Real-time controller coordinate analysis against predefined poses
- **Assessment Logic:** 10-minute timer, three-attempt threshold, automatic progression
- **Data Persistence:** Score tracking with trainee name, section, aircraft type, level, and timestamp
- **Animation System:** Unity Animator Controller for dynamic aircraft responses

## 🎓 Educational Impact

Evaluated using ISO/IEC 25010:2011 software quality standards and iUXVR questionnaire with:
- 11 IT experts and practitioners
- 41 aviation information systems students
- 5 ground marshalling instructors

**Results demonstrated strong compliance** across functional suitability, performance efficiency, reliability, and user satisfaction metrics, confirming the system's effectiveness as an alternative learning tool for ground marshalling education.

## 📋 Repository Structure

```
├── Assets/
│   ├── Scenes/           # Training, Practice, Assessment, Settings scenes
│   ├── Scripts/           # C# controllers and recognition logic
│   ├── Prefabs/           # Reusable game objects
│   ├── Animations/        # Aircraft response animations
│   ├── Models/            # 3D assets (aircraft, airport environment)
│   └── UI/                # Interface elements and HUD
├── ProjectSettings/       # Unity project configuration
└── Documentation/         # User guides and technical documentation
```

## 🚀 Getting Started

### Hardware Requirements
- Meta Quest 2 VR headset
- Oculus Touch controllers
- Oculus Quest Link Cable (for development)
- Development PC with:
  - 64-bit Intel/AMD processor
  - NVIDIA GTX 1060Ti / RTX 580 or better
  - 16GB RAM minimum
  - SSD with 150GB free space
  - Windows 10/11 64-bit

### Software Requirements
- Unity 2021.3.45f1 LTS
- Visual Studio 2022
- OpenXR Plugin
- Meta XR SDK
- Blender 4.3 (for asset modifications)

### Installation
1. Clone the repository with Git LFS
2. Open project in Unity 2021.3.45f1
3. Import required packages via Package Manager
4. Build and deploy to Meta Quest 2

## 📝 License

This project is developed for academic purposes at the National Aviation Academy of the Philippines, Institute of Computer Studies.

---

**Keywords:** Virtual Reality, Ground Marshalling, Aviation Training, Motion Capture, XR, Unity, Meta Quest 2, Educational Technology
