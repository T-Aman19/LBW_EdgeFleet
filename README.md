# LBW Detection

This project provides a computer vision-based approach for detecting LBW (Leg Before Wicket) events in cricket using video analysis and Python.

## Description

The repository contains scripts and resources to process cricket match footage, detect the ball, batsman, and pitch, and analyze LBW scenarios. The solution leverages OpenCV and related libraries for video frame analysis.

## Directory Structure

```
lbw-detection/
├── ball_detect.py      # Ball detection logic
├── batsman.py         # Batsman detection and tracking
├── lbw.mp4            # Sample cricket video for testing
├── main.py            # Main entry point for LBW detection
├── pitch.py           # Pitch area detection
├── requirements.txt   # Python dependencies
└── __pycache__/       # Compiled Python files
```

## Requirements

- Python 3.8 or higher
- OpenCV
- numpy

Install all dependencies with:

```bash
pip install -r requirements.txt
```

## Usage

1. Place your cricket match video (e.g., `lbw.mp4`) in the `lbw-detection` directory.
2. Run the main script:

```bash
python main.py
```

The script will process the video and output LBW detection results.


For questions or feedback, please contact [tyagi0776@gmail.com](mailto:tyagi0776@gmail.com).