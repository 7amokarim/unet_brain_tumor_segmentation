# Brain Tumor Segmentation using U-Net

## Overview
This project implements a U-Net deep learning model for medical image segmentation.

The goal is to detect and segment brain tumors from MRI images.

---

## Dataset
The dataset consists of:
- Brain MRI images
- Corresponding segmentation masks

The data was loaded manually and preprocessed before training.

---

## Preprocessing
- Images were resized to (128 × 128)
- Pixel values were normalized
- Masks were converted to binary format

---

## Model
A U-Net architecture was implemented using TensorFlow/Keras.

The model consists of:
- Encoder (downsampling)
- Bottleneck
- Decoder (upsampling)

---

## Training
- Optimizer: Adam
- Loss Function: Binary Crossentropy
- Metric: Accuracy

---

## Results
- Training accuracy reached ~96%
- The model was able to segment tumor regions from MRI scans

---

## Output
The model generates predicted masks highlighting tumor areas.

---

## Run the Project
You can run the notebook on Google Colab:

[Open in Colab](https://colab.research.google.com/drive/1VxN1gaW5-YMCxGqdyWlJKcTtgiMzpl2y?usp=sharing)

---

## Conclusion
This project demonstrates the effectiveness of U-Net in medical image segmentation tasks.
