#  Binary Image Segmentation of Squirrels using U-Net

> A deep learning-based image segmentation project using the **U-Net architecture** to identify and segment squirrels from images.  
> The model was trained on 500 images and evaluated using accuracy and Intersection over Union (IoU), achieving strong performance in distinguishing squirrel regions from background.

---

## 📖 Project Overview
This project was completed as part of my internship in the **Department of Geography, Environment, and Geomatics at the University of Ottawa**.

The goal was to apply deep learning techniques for **binary image segmentation** of squirrels, focusing on distinguishing foreground (squirrel) from background using pixel-level classification.

---

## 🎯 Objectives
- Develop a deep learning model for binary image segmentation  
- Segment squirrel regions from background environments  
- Improve dataset quality using preprocessing and masking techniques  
- Evaluate model performance using IoU and accuracy  

---

## Methodology

### Dataset Preparation
- Collected 500 squirrel images  
- Applied OpenCV-based masking to generate binary labels  
- Created segmentation masks using thresholding techniques  

### Preprocessing
- Resized images to a consistent resolution  
- Normalized pixel values  
- Applied data augmentation to improve model generalization  

### Model Development
- Implemented **U-Net architecture** for image segmentation  
- Used **Binary Cross-Entropy loss function**  
- Trained model on labeled dataset  

---

## 📈 Evaluation Metrics
- Accuracy  
- Intersection over Union (IoU)  
- Visual inspection of segmentation masks  

---

## 🛠️ Tools & Technologies
- Python  
- TensorFlow / Keras  
- OpenCV  
- NumPy  
- Matplotlib  

---
## 📊 Results

- **Intersection over Union (IoU): 0.79**, indicating strong overlap between predicted and ground truth masks and serving as the primary evaluation metric for segmentation quality  
- **Pixel-wise accuracy: ~86%**, reflecting the percentage of correctly classified pixels (background and foreground combined). 
- The model produces probability-based segmentation masks with values ranging from 0 to 1, successfully distinguishing squirrel regions from background. 


## 🌍 Relevance to GIS & Environmental Analysis
This project demonstrates how deep learning can be applied to:
- Wildlife detection and monitoring  
- Environmental image segmentation  
- Geospatial and remote sensing image analysis  

---

## Internship Experience
Department of Geography, Environment, and Geomatics  
University of Ottawa  

---

## Author
Ferdousi Sultana  
MSc Geography | GIS & Remote Sensing | Deep Learning Applications  
