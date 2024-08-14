# objectsDetectionUsingVideo
Real-Time Object Detection with YOLOv5 and SAM
This repository contains code for a real-time object detection system using the YOLOv5 model, enhanced with the Segment Anything Model (SAM) for precise image segmentation. The system processes video streams, detects multiple objects in real-time, and saves the output with annotated bounding boxes. Additionally, it logs detection results in JSON format for further analysis and integration.

Features
Real-Time Object Detection: Utilizes the YOLOv5 model for fast and accurate detection of objects in video streams.
Image Segmentation: Integrates SAM to perform detailed image segmentation, improving the precision of object detection.
Video Output: Saves processed video files with annotated bounding boxes around detected objects.
JSON Logging: Stores detection results, including object labels, confidence scores, and bounding box coordinates, in a JSON format for easy access and analysis.
Customizable: Easily modify the code to work with different models or datasets, or to adapt the output format to your needs.
Usage
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/object-detection-yolov5-sam.git
cd object-detection-yolov5-sam
Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Run the object detection script:

bash
Copy code
python ObjectDetectionYolo.py --input_video path/to/your/video.mp4 --output_video path/to/save/output.mp4 --output_json path/to/save/output.json
View the JSON output:
Load and print the contents of the output_results.json file to inspect the detection results.

Requirements
Python 3.7+
PyTorch
OpenCV
YOLOv5
Segment Anything Model (SAM)

