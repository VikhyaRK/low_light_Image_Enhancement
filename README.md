# Low-Light Image Enhancement using Zero-DCE  

## Overview  
This project implements a self-supervised low-light image enhancement model based on the Deep Curve Estimation Network (DCE-Net). The model enhances visibility in low-light images without requiring reference images by applying iterative non-linear transformations guided by domain-specific loss functions.  

## Key Features  
1. **Model Architecture**: Built a custom DCE-Net using convolutional layers to estimate enhancement curves iteratively applied to input images.  
2. **Loss Functions**: Designed and implemented custom loss functions to ensure:  
   - **Spatial Consistency**: Preserving structural details.  
   - **Illumination Smoothness**: Ensuring smooth brightness transitions.  
   - **Color Constancy**: Maintaining natural color balance.  
   - **Exposure Correction**: Adjusting brightness to optimal levels.  
3. **Data Preprocessing**: Created a data pipeline using TensorFlow to load, resize, and normalize low-light images efficiently.  
4. **Model Training**: Trained the model on a dataset of 1,000+ low-light images using custom loss functions and the Adam optimizer.  
5. **Evaluation**: Achieved robust performance on benchmark datasets by visualizing and analyzing enhancement results.  

## Steps I Followed  
1. Defined and built the DCE-Net architecture using TensorFlow and Keras.  
2. Developed a data pipeline for preprocessing and batching low-light images.  
3. Designed custom loss functions to guide the enhancement process.  
4. Compiled and trained the model using TensorFlow's training API and tracked loss metrics.  
5. Evaluated the model on unseen test datasets and visualized enhanced images.  

This project highlights advanced techniques in self-supervised learning and computer vision for real-world low-light image enhancement applications.
