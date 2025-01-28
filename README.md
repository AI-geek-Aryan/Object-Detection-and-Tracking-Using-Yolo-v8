# Object Detection using YOLOv8 🎥🔦

Welcome to the **Object Detection and Tracking using YOLOv8** project! This repository demonstrates how to leverage the powerful YOLOv8 model to detect and track objects in real-time.

---

## Features ✨

- **Real-Time Object Detection**: Detect objects with high accuracy using the latest YOLOv8 model.
- **Tracking Capabilities**: Draw bounding boxes and track objects frame by frame.
- **Customizable Confidence Threshold**: Filter predictions based on your desired confidence level.
- **Wide Object Class Support**: Detect objects from a comprehensive COCO dataset class list.

---

## Requirements 📂

Make sure you have the following installed:

- Python 3.8+
- OpenCV (`cv2`)
- NumPy
- Ultralyitcs YOLO library (`ultralytics`)

Install dependencies using:

```bash
pip install opencv-python-headless numpy ultralytics
```

---

## Getting Started 🚀

Follow these simple steps to set up and run the project:

### 1. Clone the Repository

```bash
git clone https://github.com/<AI-geek-Aryan
>/object-detection-yolov8.git
cd object-detection-yolov8
```

### 2. Download the YOLOv8 Model

Ensure you have the YOLOv8 weights file (`yolov8n.pt`). You can download it from the [official YOLOv8 repository](https://github.com/ultralytics/ultralytics).

### 3. Run the Code

Execute the script to start object detection:

```bash
python object_detection.py
```

---

## How It Works 🕵️‍♂️

1. **Load YOLO Model**: The script loads the pre-trained YOLOv8 model.
2. **Video Input**: You can use a webcam or provide a video file as input.
3. **Detection and Tracking**: Objects are detected, and bounding boxes are drawn in real time.
4. **Display Results**: The processed video is displayed with bounding boxes and labels.

---

## Key Functions 🔠

- **`detect_and_track_objects(frame, model)`**:

  - Performs object detection using the YOLOv8 model.
  - Parses results to extract bounding boxes, confidence scores, and class IDs.

- **Class Labels**:

  - The script includes a comprehensive list of COCO dataset class labels for easy customization.

---

## Demo 🎥

Run the script and point your webcam or provide a video file to see YOLOv8 in action! Press **`q`** to stop detection.

---

## Further Queries ✉️

If you have any questions or need support, feel free to reach out:
**Email**: aryan070sharma@gmail.com

---

## Contributing 📚

Contributions are welcome! Feel free to submit issues or pull requests to improve the project.

---

## License 🔒

This project is licensed under the [MIT License](LICENSE).

---

Happy Coding! ✨

