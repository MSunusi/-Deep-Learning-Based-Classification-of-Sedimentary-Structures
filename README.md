# Deep Learning-Based Classification of Sedimentary Structures in Drill Core Images using YOLOv11

<div align="center">
  <img src="https://github.com/MSunusi/-Deep-Learning-Based-Classification-of-Sedimentary-Structures/blob/main/train_images.jpg?raw=true" alt="Training Image" width="500"/>
  <p><strong>Figure 1:</strong> Training Image</p>
</div>

<div align="center">
  <img src="https://github.com/MSunusi/-Deep-Learning-Based-Classification-of-Sedimentary-Structures/blob/main/output_bounding_box.jpg?raw=true" alt="Detected Structures" width="500"/>
  <p><strong>Figure 2:</strong> Detected Sedimentary Structures</p>
</div>



---

## 🧠 Overview

This project presents a deep learning pipeline that identifies and classifies sedimentary structures in geological core images using the YOLOv11 object detection model. The model helps geologists and researchers automatically recognize key sedimentary features critical for understanding depositional environments and supporting hydrocarbon exploration.

the annotated 222 geological core images with 5 classes were trained  the classification are:

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

### 1. Create a virtual environment (optional but recommended)

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

```


### 2. Clone the Repository

```bash
git clone https://github.com/MSunusi/-Deep-Learning-Based-Classification-of-Sedimentary-Structures.git
cd -Deep-Learning-Based-Classification-of-Sedimentary-Structures

```

### 3. Install dependencies

```bash
 pip install -r requirements.txt

```

### open for collaburation

we are open for collaburation to improve the model evn Batter should you have interest reach out through the mail below 

- **Mail: sunusimuhammada@gmail.com**
- **linkedin: https://www.linkedin.com/in/sunusi-ibrahim-muhammad-19a654236?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3Bjx10aYerR3eR4hT7ZuCEOw%3D%3D**



