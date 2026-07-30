---
title: CE17 Skin Disease Classifier
emoji: 🩺
colorFrom: blue
colorTo: green
sdk: streamlit
sdk_version: 1.60.0
app_file: app.py
pinned: false
---

# CE17 Skin Disease Classifier Using CNN

## CE17 Mini Project

This project uses a Convolutional Neural Network (CNN) based on MobileNetV2 to classify skin disease images into two categories:

- Acne
- Eczema

## Dataset

The dataset contains:

- Training Images: 1,243
- Testing Images: 177

Total Images: **1,420**

The dataset was obtained from Kaggle and organized into separate training and testing folders.

## Model Performance

- Training Accuracy: **92.52%**
- Validation Accuracy: **88.70%**
- Validation Loss: **0.3269**

## Technologies Used

- Python
- TensorFlow/Keras
- MobileNetV2
- Streamlit
- NumPy
- Pillow
- Matplotlib

## How to Run

1. Install the required packages:

```bash
pip install -r requirements.txt
```

2. Run the application:

```bash
streamlit run app.py
```

3. Upload a skin disease image.

4. The application predicts whether the image is:

- Acne
- Eczema

and displays the prediction confidence.

## GitHub Repository

https://github.com/novajagen088-dot/CE17_Skin_Disease_Classifier

## Author

**DAVID ITORO**