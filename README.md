# Adaptive-image-enhancement
# 📸 Adaptive Image Enhancement

This repository implements **Adaptive Image Enhancement techniques** to improve the visual quality of digital images under challenging conditions like **low light, high dynamic range, and noisy environments**.  
The project compares **Median Filtering** (traditional approach) with the proposed **Hybrid Adaptive Histogram Equalization (CLAHE-based)** method.  

---

## 🚀 Features
- 🟢 **Median Filtering (Baseline):** Removes noise using kernel-based smoothing.  
- 🟢 **Hybrid Adaptive CLAHE (Proposed):**  
  - Works in **YCrCb color space** (enhances brightness without color distortion).  
  - Dynamically adjusts **clip limits** using local contrast variance.  
  - Enhances both bright and dark regions while minimizing noise.  
- 🟢 **Quality Evaluation:**  
  - **PSNR (Peak Signal-to-Noise Ratio)**  
  - **MSE (Mean Squared Error)**  
  - **SSIM (Structural Similarity Index)**  
- 🟢 **Visualization Tools:**  
  - Side-by-side image comparison  
  - Metric plots (PSNR, MSE, SSIM vs. parameters)  
  - Grid of enhanced outputs  

---

## 📊 Results
- **Proposed method outperforms median filtering** in detail preservation and contrast enhancement.  
- Achieved:  
  - ✅ **PSNR: 59.99 dB** (vs. 35.35 dB for filtering)  
  - ✅ **MSE: 0.07** (vs. 18.96 for filtering)  
- Applicable in **photography, surveillance, healthcare imaging, and autonomous driving**.  

---

## 🛠 Tech Stack
- **Language:** Python 3.7+  
- **Libraries:**  
  - OpenCV (`cv2`) – image processing  
  - NumPy – numerical computations  
  - Matplotlib – visualization  
  - scikit-image – SSIM metric
    <img width="1920" height="1032" alt="Image" src="https://github.com/user-attachments/assets/890b5dfd-d159-4eaa-ae40-64d0caef4d32" />

---

## 📂 Repository Structure

