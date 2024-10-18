# Live Cam Depth Estimation using Depth Anything V2

This repository provides a simple interface for real-time monocular depth estimation using a live camera feed. It uses the `Depth-Anything-V2-Small-hf` model from Hugging Face to predict depth maps from the camera stream.

## Features

- **Live Camera Feed**: View the live camera stream and its corresponding depth estimation in real-time.
- **Depth Map Generation**: Colorized depth map using the Jet colormap to highlight depth variations.
- **Toggle Webcam Stream**: Start and stop the camera stream with a simple toggle button.
- **Web-Based Interface**: Easy-to-use interface with `ipywidgets` for smooth control.

## Demo
You can see the project in action in the demo video:  
[Watch the demo](https://github.com/zijie-cai/live-depth-anything-v2/blob/0257614b73c27fb3340e2581dbb824d8507d5f5b/live_depth.mp4)

## Setup

Clone the repository and install the required dependencies:
```bash
git clone <repository_url>
cd live_cam_depth_estimation
pip install -r requirements.txt
