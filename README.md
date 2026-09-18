# Lane Detection System

## Overview

This project implements a Lane Detection System using Computer Vision techniques. It is designed to process video feeds (or static images) from a vehicle's dashcam and identify lane markings in real-time. This project serves as a foundational module for Advanced Driver Assistance Systems (ADAS) and Autonomous Vehicles.

This project was built for the Flipped Course Evaluation of the Computer Vision subject.

## Features

* **Real-time Video Processing:** Highlights lane boundaries on pre-recorded video feeds.
* **Image Processing:** Supports processing of single dashboard images.
* **Classic CV Pipeline:** Utilizes Grayscale conversion, Gaussian Blur, Canny Edge Detection, and Hough Line Transform.
* **Configurable:** All image processing parameters (thresholds, kernel sizes) are easily accessible in `config.py`.
* **Modular Design:** The pipeline is separated into distinct, testable modules.

## Technologies and Tools Used

* **Python 3.x:** Core programming language.
* **OpenCV (`opencv-python`):** Used for all image and video processing tasks.
* **NumPy (`numpy`):** Used for matrix/array operations and calculating mathematical averages for line slopes.
* **Unittest:** Standard Python library used for automated testing.

\## Project Structure



```text

Lane-Detection\_Computer-Vision/

│

├── src/

│   ├── edge\_detector.py

│   ├── line\_detection.py

│   ├── pipeline.py

│   └── roi.py

│

├── tests/

│   └── test\_pipeline.py

│

├── config.py

├── main.py

├── requirements.txt

├── dashcam.jpg

├── processed\_image.jpg

├── statement.md

├── README.md

└── .gitignore

```

