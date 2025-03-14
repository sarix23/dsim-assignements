# 🎯 **Digital Signal & Image Management Assignments**  

📌 This repository contains **four assignments** completed for the **Digital Signal and Image Management** course of MSc in Data Science at University of Milano - Bicocca. 
Each assignment focuses on key **audio and image processing** techniques, implementing fundamental concepts from scratch.  

## 📂 **Assignments Overview**  

### 🎵 **1. Zero-Crossing Rate (ZCR) for Audio Classification**  
- Implements **ZCR** from scratch to analyze single-channel audio signals.  
- Evaluates classification performance on the **Free Spoken Digit Dataset**.  
- Compares **ZCR alone vs. ZCR combined with other features**.  
- **Libraries used**: `numpy`, `scipy`, `sklearn`.  

### 🎶 **2. Spectrogram & MFCC Feature Extraction**  
- Extracts **Spectrogram** and **MFCC** features for audio classification.  
- Ensures a **fixed feature size** before unrolling to 1D.  
- Uses **Librosa** for audio processing.  
- **Libraries used**: `librosa`, `numpy`, `scipy`, `sklearn`.  

### 🖼️ **3. YCbCr Color Space & Image Compression**  
- Explores **YCbCr color space** and its role in image compression.  
- Applies **Gaussian blur** to **Chroma** (Cb, Cr) and **Luma** (Y) channels.  
- Visualizes the impact of **color compression** on human perception.  
- **Libraries used**: `skimage`, `numpy`, `matplotlib`.  

### 📸 **4. Image Stitching with Homography**  
- Implements **image stitching** by detecting and matching keypoints.  
- Computes **homography** and applies **image warping** for alignment.  
- Combines two overlapping images into a seamless panorama.  
- **Libraries used**: `opencv (cv2)`, `numpy`, `matplotlib`.  

## 🔧 **How to Run the Code**  
Ensure all required libraries are installed:  
```bash
pip install numpy scipy sklearn librosa skimage matplotlib opencv-python
```

Run each script separately in Google Colab or a local Python environment.

🚀 This repository showcases fundamental techniques in audio & image processing, emphasizing manual implementation for deeper understanding! 🎬🎨
