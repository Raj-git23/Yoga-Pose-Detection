# 🧘 Yoga Pose Detection and Classification

A real-time yoga pose detection and classification system using **MoveNet** for keypoint detection and **MLP / Random Forest** for classification.

---

## 🔍 Features

- Real-time pose detection using webcam
- Image and video file input support
- Pose keypoint extraction via MoveNet
- Classification using MLP (TensorFlow)
- Optimized with threading for faster multi-person inference
- Easy-to-train custom models using keypoint data

---

## 🗂️ Project Structure

```

Yoga-Pose-Detection/
├── utils/yoga_keypoints_moveNet.csv        # Dataset with 34 keypoints + label
├── model training collab/YOLO+Mediapipe_40Pose.ipynb        # Contain model training code
├── models/yoga_pose_model_40.h5        # Main trained model to use
├── yoga_classifier_model_implementation.ipynb     # Main model implementation code
├── README.md                         # Documentation

````

---

## 📌 Dependencies

* TensorFlow
* OpenCV
* Scikit-learn
* Pandas
* Joblib

---
