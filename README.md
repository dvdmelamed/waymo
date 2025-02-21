# Waymo Self-Driving Car 3D Viewer

An interactive 3D viewer for a self-driving car model using Three.js. This project provides a web-based 3D visualization of a self-driving car that users can rotate and examine from different angles.

## Features

- Interactive 3D model viewing
- Orbit controls for rotation and zoom
- Realistic lighting and shadows
- Responsive design
- Modern sky background
- Ground plane with shadows

## Technologies Used

- Three.js for 3D rendering
- GLTFLoader for model loading
- OrbitControls for camera control
- Modern JavaScript (ES6+)

## Usage

Visit the live site at: https://dvdmelamed.github.io/waymo/

You can interact with the 3D model using:
- Left mouse button: Rotate the view
- Mouse wheel: Zoom in/out
- Right mouse button: Pan the view

## Local Development

To run this project locally:

1. Clone the repository
```bash
git clone https://github.com/dvdmelamed/waymo.git
```

2. Navigate to the project directory
```bash
cd waymo
```

3. Serve the files using a local server
(You can use any local server, for example Python's built-in server):
```bash
python -m http.server 8000
```

4. Open your browser and visit `http://localhost:8000`

## License

This project is open source and available under the MIT License. 