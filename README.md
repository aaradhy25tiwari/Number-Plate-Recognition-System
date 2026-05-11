# Number-Plate-Recognition-System

An Automatic Number Plate Recognition (ANPR) system built using Python and YOLOv8. This project detects vehicle number plates from images or video streams and processes them efficiently.

## Features

- **Accurate Detection**: Leverages YOLOv8 for high-speed and accurate bounding box detection of vehicle number plates.
- **Interactive Notebook**: Provided as a Jupyter Notebook (`.ipynb`) for an interactive, step-by-step walkthrough of the pipeline.


## Prerequisites

Before you start, ensure that you have the following installed on your system:

- Python 3.8+
- Git (for cloning the repository)
- Jupyter Notebook or JupyterLab

## Installation

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/Number-Plate-Recognition-System.git
   cd Number-Plate-Recognition-System
   ```

2. (Optional but recommended) Create and activate a Python Virtual Environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```

3. Install the required dependencies:
   ```bash
   pip install ultralytics opencv-python jupyterlab
   # (Add other requirements here like easyocr, pytesseract, matplotlib, etc.)
   ```

## Usage

1. Launch Jupyter Notebook in your project directory:
   ```bash
   jupyter notebook
   ```

2. Open the main `.ipynb` file.
3. Follow the sequence of cells to load the YOLOv8 weights, process your input images/videos, and view the output detections.

## How It Works

This application utilizes the `ultralytics` YOLOv8 object detection model, which has been trained to recognize the specific features of vehicle number plates. The pipeline reads image/video inputs via OpenCV, passes them through the inference model, and renders bounding boxes around detected plates.

## Limitations

- Detection accuracy may vary depending on lighting conditions, camera angles, and image resolution.

