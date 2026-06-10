# 🚗 Distracted Driver Detection System using YOLOv11

An AI-powered Computer Vision system built using **YOLOv11** to detect and classify distracted driving behaviors in real time.
The model identifies multiple driver activities and highlights them with bounding boxes and class labels for enhanced road safety monitoring.

---

## 📌 Overview

Distracted driving is one of the leading causes of road accidents.
This project uses **YOLOv11 object detection** to recognize different driver behaviors from images/videos and classify them into multiple categories.

The system can detect behaviors such as:

* 📱 Texting
* 🥤 Drinking
* 😴 Sleeping
* 🥱 Yawning
* 🚘 Normal driving
* and more...

Each detected behavior is highlighted with:

* Bounding boxes
* Confidence scores
* Behavior class labels

---

## 🚀 Features

* ✅ Real-time distracted driver detection
* ✅ YOLOv11-based object detection
* ✅ 10 different driver behavior classes
* ✅ Bounding box visualization
* ✅ Data augmentation for improved accuracy
* ✅ Roboflow dataset integration
* ✅ Deep learning training pipeline
* ✅ Detection on images/videos

---

## 🧠 Detected Driver Behaviors

The model is trained on multiple driver activity classes including:

* Normal Driving
* Texting
* Drinking
* Sleeping
* Yawning
* Calling
* Looking Away
* Reaching Behind
* Talking
* Other distracted behaviors

---

## 🛠️ Tech Stack

* **Python**
* **YOLOv11**
* **OpenCV**
* **Roboflow**
* **NumPy**
* **Google Colab**
* **Jupyter Notebook**

---

## 📂 Project Structure

```bash id="u82ks1"
yolo-detection-tcs/
│── tcs.ipynb                 # Main notebook
│── sample_outputs/           # Detection outputs
│── requirements.txt
│── README.md
│── .gitignore
```

---

## ⚙️ Dataset & Training

The dataset was obtained using **Roboflow** and enhanced using various **data augmentation** techniques to improve model generalization and robustness.

### Augmentation Techniques Used

* Rotation
* Flipping
* Scaling
* Brightness adjustments
* Noise injection

The model was trained on annotated driver images containing multiple distraction categories.

---

## ▶️ Run the Project

Clone the repository:

```bash id="j92ls1"
git clone https://github.com/saniakhan20/yolo-detection-tcs.git
cd yolo-detection-tcs
```

Install dependencies:

```bash id="p82ls1"
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash id="m82ls1"
jupyter notebook
```

Open:

```text id="q81ks2"
tcs.ipynb
```

Run all cells to:

* train the YOLOv11 model
* perform driver behavior detection
* visualize predictions

---

## 📈 Results

The trained model successfully detects and classifies distracted driving behaviors with bounding boxes and confidence scores.

### Example Output

* Driver detected as **Texting**
* Driver detected as **Sleeping**
* Driver detected as **Drinking**
* Driver detected as **Normal Driving**

The system helps improve:

* Driver monitoring
* Road safety analysis
* Intelligent transportation systems

---

## 🌱 Future Improvements

* Real-time webcam integration
* Alert system for dangerous behaviors
* Deployment using Flask/Django
* Mobile/Edge AI deployment
* Performance optimization for low-latency inference

---

## 📌 Note

Large datasets, trained model weights (`.pt` files), and backup archives are excluded from this repository due to GitHub file size limitations.

---

## 👩‍💻 Author

**Sania Khan**

* 💼 LinkedIn: https://www.linkedin.com/in/sania-khan-1a250a370/
* 🧠 LeetCode: https://leetcode.com/saniaakhann/

---

## ⭐ Contributing

Contributions, suggestions, and improvements are welcome!

If you found this project useful, consider giving it a ⭐ on GitHub.
