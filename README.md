YOLOv7 ASL A-Z Recognition

Project Overview
This project implements **YOLOv7** for recognizing American Sign Language (ASL) gestures from A to Z. The model is trained to detect and classify ASL hand signs in real-time.

Getting Started
1. Clone the Repository
```bash
!git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

2. Install Dependencies
Ensure you have the necessary libraries installed:
```bash
!pip install -r requirements.txt
```

3.  Download YOLOv7 Weights
```bash
!wget https://github.com/WongKinYiu/yolov7/releases/download/v0.1/yolov7.pt
```

Usage
 Run the Model in Colab
1. Open the Colab notebook: ASL_ATOZ_YOLOv7.ipynb
2. Execute the cells step by step to:
   - Load YOLOv7 model
   - Perform inference on ASL hand sign images/videos

Run Inference on an Image
```bash
!python detect.py --weights yolov7.pt --source asl_test_image.jpg --conf 0.25
```

Model Performance
- Trained using **YOLOv7** on an ASL dataset.
- Accuracy: _(Add your results if available)_
- Real-time performance: _(FPS details if applicable)_

Project Structure
```
/your-repo-name
│── ASL_ATOZ_YOLOv7.ipynb   # Google Colab Notebook
│── detect.py                # YOLOv7 detection script
│── requirements.txt         # Required Python libraries
│── README.md                # Project documentation
```
Feel free to submit issues or pull requests to improve the project.
---
Author: NISHITA SHARMA  
Contact: nishitas0502@gmail.com 
