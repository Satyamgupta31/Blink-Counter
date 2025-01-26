
# BlinkCounter

**BlinkCounter** is a real-time blink detection application built with Python and OpenCV. It uses facial landmark detection to track user blinks and updates a counter with each blink. The project demonstrates the use of computer vision techniques for interactive applications.

## Features
- Real-time blink detection using Python and OpenCV.
- Accurate tracking of eye movements with Dlib’s facial landmark detection.
- Dynamic counter that updates each time a blink is detected.
- Visual feedback with on-screen alerts and counter display.
- Lightweight and responsive, designed to work with a standard webcam.

## Installation

To run BlinkCounter on your local machine, follow the instructions below:

### Prerequisites

- Python 3.x
- OpenCV
- Dlib

### Steps

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/your-username/blinkcounter.git
   ```
2. Navigate to the project folder:
   ```bash
   cd blinkcounter
   ```
3. Install required Python libraries:
   ```bash
   pip install opencv-python dlib
   ```

4. Run the application:
   ```bash
   python blinkcounter.py
   ```

### Usage
1. Open the application, and the webcam will activate.
2. The counter will start, tracking the number of blinks you make.
3. The on-screen display will show the current blink count and provide feedback when a blink is detected.

## Contributing

Feel free to fork the project, open issues, or submit pull requests to improve the application.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
