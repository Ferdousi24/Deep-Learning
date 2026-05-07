#  Semantic Segmentation of Squirrels using U-Net

> A deep learning-based geospatial image segmentation project using the **U-Net architecture** to perform pixel-wise segmentation of squirrels from natural backgrounds.  
> The model was trained on 500 wildlife images and evaluated using Intersection over Union (IoU), demonstrating strong performance in foreground-background separation.

---

##  Project Overview

This project was completed as part of an internship in the **Department of Geography, Environment, and Geomatics at the University of Ottawa**.

The objective was to develop a deep learning pipeline for **semantic segmentation of wildlife imagery**, enabling pixel-level extraction of squirrel regions from complex environmental backgrounds.

---

## Objectives

- Develop a deep learning model for semantic segmentation of wildlife images  
- Perform pixel-level separation of squirrels from background environments  
- Apply image preprocessing and masking techniques to improve training data quality  
- Evaluate model performance using IoU and segmentation quality metrics  

---

## Methodology

### Dataset Preparation
- Collected 500 squirrel images  
- Generated binary segmentation masks using OpenCV-based masking techniques  
- Created pixel-level ground truth labels for training  

###  Preprocessing
- Resized images to uniform resolution  
- Normalized pixel values  
- Applied data augmentation to improve model generalization  

###  Model Development
- Implemented **U-Net architecture** for semantic segmentation  
- Used **Binary Cross-Entropy loss function**  
- Trained model on labeled dataset for pixel-wise prediction  

---

## Evaluation Metrics

- **Intersection over Union (IoU): 0.79** → primary metric for segmentation quality  
  
- Visual validation of predicted segmentation masks  

---

##  Tools & Technologies

- Python  
- TensorFlow / Keras  
- OpenCV  
- NumPy  
- Matplotlib  

---

##  Results

- The model achieved an **IoU of 0.79**, indicating strong overlap between predicted and ground truth masks  
- Successfully learned to separate squirrel foreground regions from complex natural backgrounds  
- Produced probability-based segmentation masks (0–1 range) with high confidence in predictions  

---

##  Relevance to GIS & Environmental Applications

This project demonstrates the application of deep learning in geospatial workflows, particularly for:

- Wildlife monitoring and habitat analysis  
- Environmental image segmentation  
- Automated extraction of spatial features from imagery  
- Integration of AI with geospatial data science workflows  

---

## Internship Context

Department of Geography, Environment, and Geomatics  
University of Ottawa  

---

## Author

Ferdousi Sultana  
MSc Geography | GIS & Remote Sensing | Geospatial AI & Deep Learning
