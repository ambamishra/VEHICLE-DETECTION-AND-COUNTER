# VEHICLE DETECTION AND COUNTER
This project implements a basic vehicle counting system using computer vision techniques. It can detect and count vehicles in video streams or pre-recorded videos.




## Features

- Real-time vehicle detection and counting.
- Support for various video input formats.
- Customizable detection parameters.


## Requirements
- Python 3.7 or later
- OpenCV
- NumPy

You can install the required libraries using:

   ```bash
pip install -r requirements.txt

```

## Usage

1. Clone this repository:
```bash
   git clone https://github.com/AbdulHadiMs/vehicle-counting-system.git
   cd vehicle-counting-system
```
2. Prepare your video input:

- Ensure you have a video file (.mp4, .avi, etc.) or a live camera stream.
3. Run the script:
```bash
python vehicle_detector.py --input <video_path> --output <output_path>
``` 
## Script Overview
```
vehicle_detector.py
```
This scripts handles:
- Loading and preprocessing video frames.
- Detecting vehicles using a trained model or predefined algorithm.
- Counting vehicles and displaying results in real time.


## Arguments
 ```
--input
```
Path to the video file or camera stream (default: webcam).
```
--output
```
Path to save the processed video.
## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your feature additions or bug fixes.


## Feedback
If you have any feedback, please reach out to me at abdulhadims11@gmail.com

Feel free to star ⭐ this repository if you find it helpful!
