# 3D Model Viewer Controls

This document provides an overview of the keyboard controls for the 3D model viewer application, designed to manipulate 3D objects in various ways, including switching models, translating, rotating, scaling, and changing colors.

## Controls

Each section below corresponds to specific functionalities implemented in the viewer.

### Question 2: Model Switching
- **Spacebar**: Switch between different 3D models (Cube, Pyramid, Prism).

### Question 3: Translation
- **Arrow Keys (Right/Left)**: Translate the model along the x-axis.
    - Right Arrow: Move right.
    - Left Arrow: Move left.
- **Arrow Keys (Up/Down)**: Translate the model along the y-axis.
    - Up Arrow: Move up.
    - Down Arrow: Move down.
- **Page Up/Page Down**: Translate the model along the z-axis.
    - Page Up: Move forward.
    - Page Down: Move backward.

### Question 4: Rotation
- **A and D**: Rotate the model around the x-axis.
    - A: Rotate counterclockwise.
    - D: Rotate clockwise.
- **W and S**: Rotate the model around the y-axis.
    - W: Rotate counterclockwise.
    - S: Rotate clockwise.
- **Q and E**: Rotate the model around the z-axis.
    - Q: Rotate counterclockwise.
    - E: Rotate clockwise.

### Question 5: Scaling
- **NumPad 1 and 3**: Scale the model along the x-axis.
    - NumPad 1: Decrease size.
    - NumPad 3: Increase size.
- **NumPad 2 and 5**: Scale the model along the y-axis.
    - NumPad 2: Decrease size.
    - NumPad 5: Increase size.
- **NumPad 0 and Enter**: Scale the model along the z-axis.
    - NumPad 0: Decrease size.
    - NumPad Enter: Increase size.

### Additional Controls
- **Tab**: Change the color of the model to a random new color.
- **Shift (Left or Right)**: Toggle spinning of the model around the currently set axis and speed.

## System Requirements
- OpenGL compatible graphics card.
- Python with Pygame and PyOpenGL installed.

## Setup Instructions
1. Install Python and pip.
2. Install the required libraries: `pygame` and `PyOpenGL`.
3. Run the application: `python display.py`.

## Usage
Launch the program and use the above controls to interact with the 3D models. The interface allows switching models, translating, rotating, scaling, and changing the visual aspects of each model in real-time.

