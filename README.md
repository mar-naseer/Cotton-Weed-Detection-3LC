# Cotton Weed Detection 

This project is based on a Kaggle competition to detect 3 types of weeds in cotton fields using computer vision.

## 🔍 Overview
- Model: YOLOv8n (edge-device constraint)
- Task: Multi-class object detection
- Metric: mAP@0.5 = 0.817

## 🌱 Classes
- Carpetweed
- Morning Glory
- Palmer Amaranth

## 🧠 Approach
Focused on **data-centric machine learning**:
- Fixed annotation errors
- Improved data quality
- Applied augmentations

## 🛠 Tech Used
- Python
- YOLOv8 (Ultralytics)
- OpenCV

## Data-Centric AI Approach
Since the model is fixed, all improvements come from data:

## Train baseline model
- Use 3LC Dashboard to identify issues (missing labels, mislabels, bbox errors)
- Fix data problems
- Retrain with improved data
- Submit and repeat
- This mirrors real production AI where model capacity is constrained.

## Dataset Details
- Training: 542 images, ~2,000 weed instances
- Validation: 133 images, ~500 weed instances
- Test: 170 images (labels withheld)
- Resolution: 1024×768 to 4032×3024 pixels
- Quality: Intentional label imperfections (production reality)

## 🤝 Contribution
This project was completed in collaboration within a team. 
Reference: https://github.com/Ibrahimak555/Computer-Vision-Projects/tree/main/Cottonweed%20Detection
