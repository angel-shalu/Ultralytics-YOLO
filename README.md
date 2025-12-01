# DeepVision Analyzer 🚀
A Multi-Model AI Detection App using Streamlit + YOLOv8

DeepVision Analyzer is an advanced, fully customizable computer-vision application built with Streamlit, YOLOv8, and OpenCV. It supports object detection, segmentation, pose estimation, tracking, and counting — all at once — on images, videos, and webcam feeds.

This app includes a modern UI, optional animated video backgrounds, multi-model inference, live progress tracking, and downloadable results.

# 🔥 Key Features
✅ Multi-Model Support

Select and run any combination of:

Object Detection

Segmentation

Pose Estimation

Tracking

Counting

# 🖼️ Supports Multiple Input Sources

Upload Image

Upload Video

Live Webcam

# 🎨 Custom Modern UI

Gradient backgrounds

Custom buttons

Animated background video (optional)

# 📥 Download Outputs

Processed image

Processed video (MP4)

# ⚙️ Tech Stack

Streamlit

YOLOv8 (Ultralytics)

OpenCV

NumPy

Pillow

# 📂 Project Structure
DeepVision-Analyzer/
│
├── app1.py          # Main Streamlit App

├── background.mp4   # Optional background video (if used)

├── yolov8n.pt

├── yolov8n-seg.pt

├── yolov8n-pose.pt

└── README.md

Run the Application
streamlit run app1.py


Your browser will open automatically at:

http://localhost:8501

# 💡 How It Works
# 🔹 Model Selection

From the sidebar:

Choose one or multiple YOLO models

Set confidence threshold

Choose input type

# 🔹 Processing

Frames are processed sequentially through each selected model

Combined output is rendered on screen

Progress bar for videos

MP4 writer for processed videos

# 🔹 Output

Images processed → download .jpg

Videos processed → download .mp4


# 📦 Models Used

yolov8n.pt – Detection

yolov8n-seg.pt – Segmentation

yolov8n-pose.pt – Pose Estimation

You can replace these with custom trained models.

# 🧠 Future Enhancements

Add OCR support

Add face recognition module

Add object tracking counters

GPU acceleration (CUDA)

Multi-page Streamlit app

# 🤝 Contributing

Pull requests are welcome!
If you add new YOLO models or modules, update the sidebar accordingly.

# 📜 License

This project is available under the MIT License.
