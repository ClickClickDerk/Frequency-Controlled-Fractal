# Frequency-Controlled Fractal

A 3D particle-based fractal system controlled by frequency, amplitude, and rotation parameters. This project uses [Three.js](https://threejs.org) and [dat.GUI](https://github.com/dataarts/dat.gui) to create an interactive, real-time fractal visualization, where users can manipulate fractal patterns using a simple GUI.

## Features

- **3D Particle System**: Generates 10,000 particles in a fractal formation.
- **Real-Time Controls**: Users can adjust the frequency, amplitude, particle size, and rotation speed of the fractal in real-time using dat.GUI.
- **Smooth Animations**: Particle system rotates and responds smoothly to user input.
- **Interactive Visualization**: Changes to parameters immediately reflect in the particle system, making it a dynamic visualization tool.

## Installation

To run this project locally, you'll need a basic HTTP server because most browsers block file system requests for security reasons.

### Steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/ClickClickDerk/Frequency-Controlled-Fractal.git
    cd Frequency-ontrolled-Fractal
    ```

2. **Serve the project**:
    You can use any simple HTTP server, such as Python's built-in server:
    ```bash
    # If using Python 3
    python -m http.server 8080

## Usage

1. **Controls**:
    - **Frequency**: Controls the wave frequency that affects the fractal pattern.
    - **Amplitude**: Modifies the intensity of the fractal movement.
    - **Particle Size**: Adjusts the size of the individual particles.
    - **Rotation Speed**: Changes the rotation speed of the particle system.

2. **Interactivity**:
    - The particle system responds in real time to changes in the control panel. You can create various visual effects by experimenting with the parameters.

## Dependencies

- [Three.js](https://threejs.org) - 3D rendering library
- [dat.GUI](https://github.com/dataarts/dat.gui) - GUI for controlling parameters

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contributing

Feel free to submit issues or pull requests if you have ideas for improvements or additional features. Contributions are always welcome!

## Acknowledgments

- The idea for this project was inspired by the creative possibilities of fractals in 3D space, and the use of particle systems in Three.js.

- nyx4d@proton.me
