# Emotion Detection with DeepFace and OpenCV

## Requirements

- Python 3.10+
- [OpenCV](https://pypi.org/project/opencv-python/)
- [DeepFace](https://pypi.org/project/deepface/)
- [TensorFlow](https://pypi.org/project/tensorflow/)
- [matplotlib](https://pypi.org/project/matplotlib/)

## Installation

Install dependencies using pip:

```sh
pip install opencv-python deepface tensorflow matplotlib
```

## Usage

### 1. Static Image Emotion Detection

Run the notebook [OpenCV.ipynb](d:\Programming languages\Web Development\DevByZero\Training and Testing\OpenCV.ipynb) to analyze emotions from `happy.jpeg`.

### 2. Real-time Emotion Detection

Run the script:

```sh
python realtime_emotion.py
```

Press `q` to exit the webcam window.

## Notes

- Make sure your webcam is connected.
- Place `happy.jpeg` in the project folder for image analysis.
- For best results, use the recommended Python environment shown