# Final-Year-Project

## Sign Language Recognition with Enhanced Video Preprocessing
This project explores the impact of different video enhancement techniques on the accuracy of an AI-powered Sign Language Recognition (SLR) system using a 3D Convolutional Neural Network (I3D) model. The experiments are conducted on the WLASL100 subset of the Word-Level American Sign Language dataset.

### Project Title:
Evaluating the Impact of Video Enhancement Techniques on a Deep Sign Language Recognition 3D CNN Model (I3D)

### 📁 Repository Structure
#### CLAHE-Training.ipynb
Notebook showing training results using CLAHE-enhanced videos.

#### HE-Training.ipynb
Notebook showing training results using Histogram Equalized videos.

#### RealESRGAN-Training.ipynb
Notebook showing training results using RealESRGAN-enhanced videos.

### 📜 Abstract
This project investigates how preprocessing via video enhancement affects the performance of deep learning-based SLR systems. Three enhancement methods were applied:

Histogram Equalization
CLAHE (Contrast Limited Adaptive Histogram Equalization)
Real-ESRGAN (Enhanced Super-Resolution GAN)

A pretrained I3D (Inflated 3D ConvNet) was trained and evaluated on each variant of the WLASL100 dataset. CLAHE-enhanced videos produced the highest classification accuracy (66%), indicating that localized contrast enhancement can improve gesture recognition performance.

### 📊 Results Summary
Enhancement Type	Accuracy (%)
Original (No Enhancement)	62%
Histogram Equalization	47%
CLAHE	66%
RealESRGAN	62%

### 🧠 Model
Architecture: Inflated 3D ConvNet (I3D)
Dataset: WLASL100 (100-word subset)
Platform: Google Colab

### ⚙️ Requirements
While only result notebooks are available in this repo, the complete implementation used the following tools:
Python
PyTorch
OpenCV
Real-ESRGAN
FFmpeg
Google Colab

### 📦 Full Code and Dataset
Due to file size limitations on GitHub, the full implementation, including:
Complete source code (data processing, training, enhancement)
All enhanced video datasets
Pretrained models and weights
...is hosted on Google Drive.

👉 Click here to access the full project on Google Drive
https://drive.google.com/drive/folders/1FRsPcOLJGY1Ckd_cH3TkxMZ-kW0jNcJZ?usp=sharing

###c📚 Related Resources
Real-ESRGAN GitHub Repository: https://github.com/xinntao/Real-ESRGAN
WLASL Dataset GitHub: https://github.com/dxli94/WLASL
