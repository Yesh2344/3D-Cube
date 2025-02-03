# OpenGL Rotating Cube Visualization

A simple Python application that creates a 3D rotating wire-frame cube using PyGame and OpenGL. The cube continuously rotates in 3D space, demonstrating basic 3D graphics programming concepts.

## Features

- 3D wire-frame cube rendering
- Continuous rotation animation
- Perspective projection
- Window-based display using PyGame

## Prerequisites

Before running this application, you need to have the following packages installed:

- Python 3.x
- PyGame
- PyOpenGL
- PyOpenGL_accelerate (recommended)

## Installation

1. Install the required packages using pip:

```bash
pip install pygame
pip install PyOpenGL
pip install PyOpenGL_accelerate
```

2. Clone this repository or download the source code.

## Usage

Run the program using Python:

```bash
python cube.py
```

The application will open a window displaying a rotating wire-frame cube. To exit the program, close the window or press Ctrl+C in the terminal.

## Code Structure

- `vertices`: Defines the 8 corners of the cube in 3D space
- `edges`: Defines the 12 edges connecting the vertices
- `draw_cube()`: Renders the cube using OpenGL lines
- `main()`: Handles program initialization and the main rendering loop

## Controls

- Close window to exit the program
- The cube automatically rotates around multiple axes

## Technical Details

- Window size: 800x600 pixels
- Field of view: 45 degrees
- Near clipping plane: 0.1
- Far clipping plane: 50.0
- Camera position: 5 units back from origin

## Contributing

Feel free to fork this repository and submit pull requests for any improvements you'd like to make.

## License

This project is open source and available under the MIT License.

## Acknowledgments

This project demonstrates basic concepts of:
- 3D graphics programming
- OpenGL usage in Python
- PyGame window management
- Real-time rendering

Email:yeswanthsoma83@gmail.com
@YeswanthSoma All Copyrights Reserved
