# tomato-leaf-disease-classification-using-efficientnet
This project is a deep learning solution for classifying **tomato leaf diseases** using **EfficientNet**, enhanced with advanced data augmentation and model optimization. It improves upon existing GitHub projects by prioritizing model performance, explainability, and real-world relevance.

---

# Project Highlights
- Built on top of an open-source dataset from **Kaggle**
- Improved baseline with **EfficientNetB0**
- Uses **Albumentations** for advanced image augmentation
- Provides **Confusion Matrix** for performance diagnostics
- Clean modular code with Jupyter (Kaggle) and compatibility for GitHub
- Fully FREE and open source, ready to reproduce or improve

---

## Dataset
- **Source**: [Kaggle - Tomato Leaf Dataset by Ashish Motwani](https://www.kaggle.com/datasets/ashishmotwani/tomato)
- **Contents**:
  - `/train`: Training set with folders for each class
  - `/valid`: Validation set
- **Classes**: Multiple diseases such as Early Blight, Late Blight, Septoria Leaf Spot, Target Spot, etc.

---

## Model Architecture
- **Backbone**: [`EfficientNetB0`](https://keras.io/api/applications/efficientnet/)
- **Preprocessing**: `ImageDataGenerator`
- **Augmentation**: `Albumentations` (Rotation, Brightness, Flip, etc.)
- **Loss Function**: `Categorical Crossentropy`
- **Optimizer**: `Adam`

---

## Results Snapshot
**Accuracy**: ~95% on validation set  
**Confusion Matrix**

---

## 📦 Dependencies

Make sure to install the following in your environment:

```bash
pip install tensorflow keras matplotlib seaborn scikit-learn albumentations opencv-python
