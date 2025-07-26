# Deep Learning-Based Classification of Sedimentary Structures in Drill Core Images using YOLOv11


<img src="https://github.com/MSunusi/-Deep-Learning-Based-Classification-of-Sedimentary-Structures/blob/main/output_bounding_box.jpg?raw=true" alt="Sedimentary Output" width="300"/>


---

## 🧠 Overview

This project presents a deep learning pipeline that identifies and classifies sedimentary structures in geological core images using the YOLOv11 object detection model. The model helps geologists and researchers automatically recognize key sedimentary features critical for understanding depositional environments and supporting hydrocarbon exploration.

We annotated and trained on 222 geological core images with 5 classes:

- Cross-bedded Sandstones
- Low-angle Cross-bedded Sandstones
- Massive Sandstones
- Parallel-laminated Sandstones
- Mud Drapes

Each class was identified based on distinct sedimentary textures and features, derived from drill cores typically used in field geology.

---

## 📦 Dataset

The annotated dataset of 222 core images is available on [Roboflow](https://app.roboflow.com).

→ Access Dataset: [Roboflow Project Link](https://app.roboflow.comhttps://universe.roboflow.com/roboflow-100/sedimentary-features-9eosf/images/SflnJqTGKFGvaQ9eSkdK)

Classes:
- Cross-bedded Sandstones
- Low-angle Cross-bedded Sandstones
- Massive Sandstones
- Parallel-laminated Sandstones
- Mud Drapes

---

## 🚀 Model Summary

- Model: YOLOv11 (You Only Look Once v11)
- Input: Annotated core images
- Output: Bounding boxes with class predictions on sedimentary structures

### Performance Metrics:

| Metric         | Score   |
|----------------|---------|
| mAP@0.5        | 0.426   |
| Precision      | 1.00    |
| Recall         | 0.76    |
| F1 Score       | 0.86    |

---

## 🛠 Installation

Follow the steps below to set up the environment and run the notebook.

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/sedimentary-yolov11.git
cd sedimentary-yolov11
