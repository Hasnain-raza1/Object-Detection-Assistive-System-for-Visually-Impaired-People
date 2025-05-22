# Object-Detection-Assistive-System-for-Visually-Impaired-People
This project is a real-time object detection and audio guidance system designed to assist visually impaired individuals in navigating their environment safely and independently. By combining computer vision and text-to-speech (TTS) technologies, the system detects objects from a video stream, estimates their distance and position (left, center, right), and provides clear spoken feedback.

🌟 Key Features
🎯 YOLOv8-based Object Detection
Detects common obstacles like people, vehicles, animals, and traffic signs in real-time using a trained YOLO model.

📏 Distance Estimation
Estimates how far detected objects are from the user using bounding box dimensions and predefined object width ratios.

🧭 Direction Awareness
Identifies whether an object is on the left, center, or right side of the user’s path.

🔁 Motion Analysis
Informs the user if an object is approaching, moving away, or very close, providing a sense of environmental dynamics.

🗣️ Speech Output with Cooldown Logic
Uses pyttsx3 for offline audio feedback and avoids repetition through a smart cooldown system.

🙈 Privacy-Aware Person Detection
Automatically blurs detected individuals' faces for privacy, useful in recorded outputs or public demonstrations.

🎥 Video Input & Output
Processes input from a video file and optionally saves the output with detection boxes and blur filters.

🔧 Technologies Used
Python 3

YOLOv8 (Ultralytics)
OpenCV
NumPy
pyttsx3 (Text-to-Speech)
Threading & Queue (for parallel speech processing)

✅ Why This Project Matters
Navigating the world can be challenging for those who are visually impaired. This project aims to bridge that gap using affordable, offline, AI-driven solutions. It can be extended into mobile apps or integrated with wearable tech like smart glasses, making independent mobility safer and more accessible.

Future Improvements
Integration with live webcam or mobile camera feed.
GPS or gyroscope support for navigation assistance.
Object prioritization for dynamic environments.
Support for multilingual voice outputs
