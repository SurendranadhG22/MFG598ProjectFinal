# Line-Following Drone with Object Detection

This project is designed to create an autonomous drone capable of following a line and detecting specific objects or circles to land on. The drone uses computer vision techniques to process visual input, track lines, and identify landing zones. This project is ideal for anyone interested in robotics, drones, and computer vision.

## Features

- **Line Following:** The drone autonomously follows a predefined path marked by a line on the ground.
- **Object Detection:** Utilizes computer vision to detect and recognize specific objects or circles as potential landing zones.
- **Autonomous Landing:** Automatically lands on the detected object, ensuring precision and safety.
- **Real-Time Processing:** Processes video input in real-time to make immediate navigation and landing decisions.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes given you have a Parrot Mambo Minidrone.

### Prerequisites

What things you need to install the software and how to install them:

```bash
sudo apt-get install python3
sudo apt-get install python3-pip
pip3 install opencv-python
pip3 install numpy
```

### Installing

A step-by-step series of examples that tell you how to get a development environment running:

1. Clone the repository:
```bash
git clone https://github.com/SurendranadhG22/MFG598Project
```

2. Navigate to the project directory:
```bash
cd line-following-drone
```

3. Install the required packages:
```bash
pip install -r requirements.txt
```

4. Run the main script:
```bash
python3 main.py
```

## Usage

To use this project, ensure your drone's camera is properly calibrated and positioned. Start the drone in a known location with a visible line and objects to detect. The system will handle the rest, guiding the drone along the path and executing landing when an object is detected.
