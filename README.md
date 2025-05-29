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
├── utils\yoga_keypoints_moveNet.csv        # Dataset with 34 keypoints + label
├── model\_training.py                 # Train MLP classifier
├── live\_pose\_detection.py            # Real-time webcam pose classification
├── image\_video\_inference.py          # Run detection on images or videos
├── artifacts/                        # Saved models and scalers
├── utils.py                          # Common utility functions
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


## 📜 License

This project is licensed under the [MIT License](LICENSE).

```
