# ProjectRobot1_2026_SunYiyao

## Micro:bit Tinybit Robot Control Project

This repository contains my individual implementation of a micro:bit Tinybit robot control project. The robot is programmed using MicroPython in Mu Editor and controlled through the Yahboom Tinybit Python library.

The project focuses on basic robot movement, direction control, speed control, and custom path control. GitHub is used to record the development process, source code, testing evidence, and project documentation.

---

## Project Overview

The aim of this project is to develop and test a micro:bit-based robot control system. The robot can move forward, change direction, run at different speeds, and follow selected movement paths.

Although the physical robot was shared sequentially due to limited hardware availability, this repository records my independent implementation, testing process, and project documentation.

---

## Main Features

### 1. Basic Forward Movement

The robot moves forward using the Tinybit motor control function. The micro:bit LED display shows a direction arrow while the robot is moving.

Source file:

```text
code/01_forward.py
```

### 2. Direction Control

The robot performs multiple movement actions, including:

* Forward movement
* Backward movement
* Left turn
* Right turn
* Spin left
* Spin right
* Stop

Source file:

```text
code/02_direction_control.py
```

### 3. Speed Control

The robot runs at different speed levels by changing the motor speed parameters. This function helps test how different speed values affect the robot’s movement.

Source file:

```text
code/03_speed_control.py
```

### 4. Custom Path Control

This is the personalised path control part of the project. Button A is used to select a path, and Button B is used to start the selected path.

The available path options are:

* L path
* O path
* D path
* Z path

Source file:

```text
code/04_path_control_LODZ.py
```

---

## Hardware and Software

### Hardware

```text
micro:bit
Yahboom Tinybit Pro robot
microUSB data cable
Computer
```

### Software

```text
Mu Editor
MicroPython
Yahboom Tinybit Python library
GitHub
```

---

## Repository Structure

```text
ProjectRobot1_2026_SunYiyao/
│
├── README.md
│
├── code/
│   ├── 01_forward.py
│   ├── 02_direction_control.py
│   ├── 03_speed_control.py
│   └── 04_path_control_LODZ.py
│
├── docs/
│   └── git_command_history.txt
│
└── video/
    └── demo_video_url.txt
```

---

## Development Process

The project was completed in several stages:

### Stage 1: Environment Setup

Mu Editor was used as the MicroPython programming environment. The Tinybit Python library was installed and checked before running the robot programs.

### Stage 2: Basic Movement

The first program was used to test whether the robot could move forward successfully.

### Stage 3: Direction and Speed Control

The robot was then tested with different movement directions and speed values.

### Stage 4: Path Control

A custom path control program was created. The robot can display and execute different path options using the micro:bit buttons.

### Stage 5: Documentation and Testing

Screenshots, testing photos, GitHub records, reports, and demo video materials were prepared for submission.

---

## GitHub and Version Control

GitHub was used to store the project files and record the development process.

The repository includes:

```text
Python source code
Git command history
Testing screenshots
Project reports
Demo video link
```

The Git command history is stored in:

```text
docs/git_command_history.txt
```

---

## Demo Video

The demo video shows the robot setup, Python code, and physical testing process.

Demo video link:

```text
video/demo_video_url.txt
```

---

## Author

```text
Name: Yiyao Sun
GitHub Username: SunYiyao525
Repository: ProjectRobot1_2026_SunYiyao
```

---

## Project Summary

This project demonstrates how a micro:bit Tinybit robot can be controlled using MicroPython. Through this project, I practised embedded programming, robot movement control, hardware testing, GitHub documentation, and technical reporting.

The final system successfully supports basic movement, direction control, speed control, and custom path control.
