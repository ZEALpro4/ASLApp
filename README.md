# American Sign Language (ASL) Recognition System

This repository contains the implementation of an **American Sign Language (ASL) Recognition System** using deep learning models. The project utilizes **YOLOv5** and **YOLOv11** for real-time sign language detection and classification.

## Project Structure
```
📂 ASL-Recognition-System
│── 📂 YOLOV5
│   ├── 📂 train/               # Training dataset
│   ├── 📂 val/                 # Validation dataset
│   ├── data.yml                # YOLO dataset configuration file
│   ├── run.py                  # Script for running YOLOv5 model
│   ├── yolov5best.pt           # Trained YOLOv5 model weights
│   ├── Sign_language_Generation_Using...  # Additional documentation or scripts
│   └── README.md               # Instructions for YOLOv5 setup
│
│── 📂 YOLOV11
│   ├── yolo11m.pt              # Trained YOLOv11 model weights
│
│── README.md                  # Main project documentation
```

## Features
- Real-time ASL detection and classification
- Implementation of **YOLOv5** and **YOLOv11** for object detection
- Trained on a dataset of ASL gestures with annotated labels
- Supports inference on live camera feed
- Model weights and scripts for training and evaluation included

## Setup Instructions
### 1. Clone the Repository
```bash
git clone https://github.com/ZEALpro4/ASLApp.git
cd ASL-Recognition-System
```

### 2. Install Dependencies
Ensure you have Python installed (preferably **Python 3.8**). Then, install the required dependencies:
```bash
pip install -r requirements.txt
```

### 3. Running the Model
#### YOLOv5
```bash
cd YOLOV5
python run.py --weights yolov5best.pt --conf 0.5
```

#### YOLOv11
(Currently, only weights are available. Model scripts need to be added for inference.)

## Dataset
The dataset consists of images annotated in XML format, with training and validation sets. It is structured as follows:
```
📂 train/
📂 val/
```

## Results
The trained models achieved accurate real-time ASL recognition. Performance metrics and sample inference results are available in their respective model folders.

## Future Enhancements
- Improve accuracy with a larger dataset
- Optimize the model for mobile deployment
- Add more ASL phrases and gestures

## Contributing
Feel free to contribute by submitting issues or pull requests!

## License
This project is licensed under the MIT License.

---
**Maintained by:** [ZealPro](https://github.com/ZEALpro4)

