# tensorflow-NHL-biomechanics

## Overview
This program is designed to analyze the biomechanics of hockey players using video footage. It leverages advanced machine learning models and computer vision techniques to assess players' movements, providing valuable insights for performance improvement and injury prevention.

## Features
- **Video Downloading**: Automatically downloads hockey gameplay videos from YouTube using `pytube`.
- **Biomechanical Analysis**: Utilizes TensorFlow and TensorFlow Hub, specifically the MoveNet SinglePose Lightning model, to detect and analyze players' biomechanics.
- **Joint Detection and Angle Calculation**: Detects key joints in player movements and calculates angles to assess biomechanical efficiency.
- **Video Processing**: Processes videos with OpenCV, marking key joints and calculating angles in real-time.

## Technologies Used
- **Python**: For scripting and backend processing.
- **TensorFlow & TensorFlow Hub**: For running the MoveNet SinglePose Lightning model.
- **OpenCV (cv2)**: For video processing and displaying results.
- **NumPy**: For numerical calculations.
- **pytube**: For downloading videos from YouTube.

## Usage Example
To analyze a specific YouTube video:
```python
download_youtube_video('https://www.youtube.com/watch?v=[video_id]', '[path_to_save_video]')
```
## Contributing
Contributions are welcome! If you have any improvements or suggestions, please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE.md) file for details.

## Acknowledgments
A heartfelt thank you to the developers of TensorFlow, TensorFlow Hub, OpenCV, and pytube for providing the tools that power this project.

