# Real-Time Face, Upper Body, and Lower Body Detection

This project demonstrates real-time detection of faces, upper bodies, and lower bodies using OpenCV and Haar cascades. The detection is performed on a live video stream captured from the webcam, and detected regions are highlighted with bounding boxes.

## Features

- **Face Detection**: Detects faces in real-time and highlights them with a red rectangle.
- **Upper Body Detection**: Detects upper bodies in real-time and highlights them with a green rectangle.
- **Lower Body Detection**: Detects lower bodies in real-time and highlights them with a blue rectangle.
- **Full-Screen Display**: The video stream with detections is displayed in full-screen mode.
- **User Interaction**: The program exits when the 'a' key is pressed.

## Installation

1. Clone this repository:

    ```bash
    git clone https://github.com/yourusername/your-repo-name.git
    cd your-repo-name
    ```

2. Install the required dependencies:

    ```bash
    pip install opencv-python
    ```

3. Download the Haar cascade XML files for face, upper body, and lower body detection:

    - [haarcascade_frontalface_default.xml](https://github.com/opencv/opencv/blob/master/data/haarcascades/haarcascade_frontalface_default.xml)
    - [haarcascade_upperbody.xml](https://github.com/opencv/opencv/blob/master/data/haarcascades/haarcascade_upperbody.xml)
    - [haarcascade_lowerbody.xml](https://github.com/opencv/opencv/blob/master/data/haarcascades/haarcascade_lowerbody.xml)

4. Place the downloaded XML files in the appropriate directory, as specified in the code.

## Usage

1. Run the script using the following command:

    ```bash
    python bodydetect.ipynb
    ```

2. The webcam feed will be displayed in full-screen mode, and the program will start detecting faces, upper bodies, and lower bodies.

3. Press the 'a' key to exit the program.

## Project Structure

- `bodydetect.ipynb`: Jupyter notebook containing the code for real-time detection.
- `README.md`: This file.

## Contributing

Contributions are welcome! If you have any improvements or suggestions, feel free to open an issue or create a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgments

- [OpenCV](https://opencv.org/) for providing the computer vision tools.
- Haar cascade files provided by the OpenCV community.

