# 🪖 Helmet Detection with OpenCV and YOLOv3

Real-time helmet detection using a webcam with OpenCV and YOLOv3.

## 🔧 Requirements

- Python 3.x  
- OpenCV  
- NumPy  
- YOLOv3 model files:
  - `yolov3-helmet.cfg`
  - `yolov3-helmet.weights`

## 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/yourusername/helmet-detection.git
cd helmet-detection

# Install dependencies
pip install opencv-python numpy

# Download YOLOv3 helmet model files and place them in the project directory
# (e.g., from Kaggle or other trusted sources)

# Run the detection script
python helmet_detection.py
Press q to exit the webcam window.

📸 Sample Output

<img src="screenshot/No Helmet.png" width="400"> 
<img src="screenshot/Helmet worn.png" width="400"> 

📌 Notes
Make sure your webcam is connected and working.

Detection accuracy depends on the model and camera quality.
