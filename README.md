# Road Mask & Lane Detection

A Classic Computer Vision project for detecting the road region and lane boundaries in road videos using Python, OpenCV, and NumPy.

This project does not use Deep Learning, CNNs, Neural Networks, or pre-trained models.

## Project Overview

The system processes a road video and detects the road region and lane boundaries using classical image-processing techniques.

The detected road area is highlighted on the video, and the lane boundaries are drawn on the processed output.

## Technologies

* Python
* OpenCV
* NumPy
* Jupyter Notebook

## Computer Vision Techniques

The project uses the following classical Computer Vision techniques:

* Video Processing
* Image Resizing
* Gaussian Blur
* Color Space Conversion
* Edge Detection
* Region of Interest (ROI)
* Hough Line Transform
* Lane Detection
* Road Mask Detection
* Image Overlay

## Processing Pipeline

```text
Input Video
     ↓
Frame Extraction
     ↓
Preprocessing
     ↓
Edge Detection
     ↓
Region of Interest
     ↓
Hough Line Transform
     ↓
Lane Detection
     ↓
Road Mask
     ↓
Visualization
     ↓
Output Video
```

## Project Structure

```text
Road-Mask/
│
├── .gitignore
├── README.md
├── RoadMask2.ipynb
└── road_mask_lane_output.mp4
```

The original input video is not included in the repository.

## Input

The project processes a road video provided by the user.

The input video is intentionally excluded from this repository to keep the repository focused on the source code and final result.

## Output

The final processed video demonstrates the detected road region and lane boundaries.

Output file:

```text
road_mask_lane_output.mp4
```

## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/Road-Mask.git
```

### 2. Open the project

```bash
cd Road-Mask
```

### 3. Install dependencies

```bash
pip install opencv-python numpy
```

### 4. Open the Notebook

Open:

```text
RoadMask2.ipynb
```

and run the cells.

## Result

The final output video contains the detected road region and lane boundaries overlaid on the original video frames.

## Limitations

Because this project uses classical Computer Vision techniques, performance can be affected by:

* Poor lighting
* Shadows
* Weather conditions
* Missing lane markings
* Curved roads
* Camera angle
* Complex road environments

## Future Improvements

Possible improvements include:

* More robust lane detection
* Better road-region segmentation
* Curved lane detection
* Real-time camera processing
* Perspective transformation
* Temporal smoothing between video frames
* Improved handling of different lighting conditions

## Learning Objectives

This project was developed to gain practical experience with:

* OpenCV
* NumPy
* Video processing
* Image preprocessing
* ROI
* Edge detection
* Hough Line Transform
* Lane detection
* Road segmentation
* Classical Computer Vision

## Author

**Amadoo**

Computer Vision / Machine Learning Student
