# Live Cam Depth Estimation using Depth Anything V2

This repository provides a simple interface for real-time monocular depth estimation using a live camera feed. It uses the `Depth-Anything-V2-Small-hf` model from Hugging Face to predict depth maps from the camera stream.





## Features

- **Live Camera Feed**: View the live camera stream and its corresponding depth estimation in real-time.
- **Depth Map Generation**: Colorized depth map using the Jet colormap to highlight depth variations.
- **Toggle Webcam Stream**: Start and stop the camera stream with a simple toggle button.
- **Web-Based Interface**: Easy-to-use interface with `ipywidgets` for smooth control.

## Demo
You can see the project in action in the demo video:  
[Watch the demo](live_depth.mov)

## Setup

Clone the repository and install the required dependencies:
```bash
git clone https://github.com/zijie-cai/live-depth-anything-v2.git
cd live-depth-anything-v2
pip install -r requirements.txt
```

## How to Run

To launch the project, use `voila` to run the notebook in a web interface:
```bash
voila live_depth.ipynb
```
