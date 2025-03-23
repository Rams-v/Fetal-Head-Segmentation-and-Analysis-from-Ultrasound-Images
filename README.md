# Comprehensive Sonographic Analysis of Fetal Head Biometry and Neurodevelopmental Deviations Across Prenatal and Intrapartum Phases

## 📌 **Project Overview**  
This project focuses on the **segmentation, classification, and analysis of fetal head biometry and neurodevelopmental deviations** using **prenatal and intrapartum ultrasound images**. It integrates **computer vision and deep learning** to improve fetal head tracking, detect abnormalities, and assess head descent during labor.  

## 🚀 **Key Features**  
- **Ultrasound Preprocessing:** NLM denoising, CLAHE contrast enhancement, and bilateral filtering.  
- **Fetal Head Segmentation:** U-Net-based deep learning model with data augmentation.  
- **Feature Extraction:** Spatial (HC, BPD, GLCM) and frequency (Wavelet entropy, Gabor energy) domain analysis.  
- **Classification:** Transfer learning models (**ResNet50, DenseNet121, EfficientNetB3, Vision Transformers**) for **normal vs. abnormal detection**.  
- **Head Descent Tracking:** PSFHS-based **Angle of Progression (AoP) and pubic symphysis positioning** analysis.  

## 🛠 **Implementation Steps**  
1. **Preprocessing & Image Enhancement** – Noise reduction, contrast enhancement, and edge preservation.  
2. **Fetal Head Segmentation** – U-Net model trained with data augmentation.  
3. **Feature Extraction** – Spatial and frequency-based analysis for improved classification.  
4. **Abnormality Classification** – Transfer learning for multi-label classification of fetal brain abnormalities.  
5. **Fetal Head Descent Analysis** – Tracking head position during labor using PSFHS ultrasound.  

## 📂 **Dataset**  
- **Prenatal Ultrasound:** Fetal brain ultrasound images labeled as normal/abnormal.  
- **Intrapartum Ultrasound (PSFHS):** Images for tracking fetal head descent and engagement.  
- **Annotations:** Ground truth segmentation masks for model training.  

## 📊 **Evaluation Metrics**  
- **Segmentation:** Dice Score, IoU, Pixel Accuracy.  
- **Classification:** Accuracy, Precision, Recall, AUC-ROC.  
- **Preprocessing Evaluation:** Structural Similarity Index Measure (SSIM), Entropy.  

## 🔥 **Upcoming Actions**  
- Fine-tune **Otsu Thresholding** for segmentation.  
- Crop **Region of Interest (ROI)** for better classification.  
- Optimize **deep learning models** for improved classification accuracy.  
- Explore **Wavelet Transform** for advanced feature extraction.  
