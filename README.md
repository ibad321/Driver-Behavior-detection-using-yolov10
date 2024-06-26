# Driver Behavior Detection using YOLOv10

This repository contains code and resources for detecting driver behaviors using the YOLOv10 object detection model. The dataset used for training is sourced from Roboflow, containing images labeled with three classes: mobile phone, seatbelt, and cigarette.

## Overview

The objective of this project is to detect and classify specific driver behaviors that could be indicators of risky driving. By using YOLOv10, we aim to create an efficient and accurate model capable of real-time detection.

## Dataset

- **Source**: [Roboflow](https://roboflow.com/)
- **Total Images**: 9,901
- **Classes**: 
  - Mobile Phone
  - Seatbelt
  - Cigarette

## Model

- **Architecture**: YOLOv10
- **Training Framework**: [Ultralytics YOLO](https://github.com/ultralytics/yolov10)

## Setup and Installation

### Prerequisites

- Python 3.10 or later
- [PyTorch](https://pytorch.org/get-started/locally/) (version compatible with your CUDA setup)
- Other dependencies listed in `requirements.txt`

### Installation

1. **Clone the repository:**

   ```sh
   git clone https://github.com/yourusername/Driver-Behavior-Detection-using-YOLOv10.git
   cd Driver-Behavior-Detection-using-YOLOv10
2. **Create and activate a virtual environment::**
    ```sh
    python -m venv
    venv source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
3. **Install the required dependencies::**
    ```sh
    pip install -r requirements.txt
## Results
The trained YOLOv10 model achieves an overall mAP50 of 0.616 on a test dataset containing 2,393 images across three classes: mobile phone, seatbelt, and cigarette.
## Acknowledgements

- Thanks to [Roboflow](https://roboflow.com/) for providing the dataset.
- Special thanks to [Ultralytics](https://github.com/ultralytics/yolov10) for their implementation of YOLOv10.

## Contact

For any inquiries or feedback, feel free to reach out:

- **Email**: ibadcui@gmail.com
- **LinkedIn**: [Ibad's LinkedIn Profile](https://www.linkedin.com/in/ibad321/)




   
    

   
