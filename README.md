# PinchVolume

PinchVolume is a Python project that utilizes the MediaPipe library for hand tracking and OpenCV for webcam capture. The program tracks specific hand landmarks, allowing the user to control the system volume through pinch gestures. Additionally, the frame rate is displayed in the video feed.

## Dependencies

Make sure you have the following dependencies installed:

- Python 3.x
- OpenCV
- Mediapipe
- NumPy
- pycaw

You can install the required dependencies using the following command:

```bash
pip install opencv-python mediapipe numpy pycaw
```

## How to Run

1. Clone the repository:

```bash
https://github.com/Sohamumap/PinchVolume

```

2. Run the script:

```bash
python pinch_volume.py
```

3. Use pinch gestures to control the system volume.
4. Press 'q' to exit the program.

## Project Structure

- `pinch_volume.py`: The main Python script containing hand tracking and volume control implementation.

## Hand Gesture Control

- Pinch your thumb and index finger together to control the volume.
- Move your pinched fingers horizontally to adjust the volume level.

