# 🖼️ SVD-Based Image Watermarking

This project explores **digital image watermarking** techniques using **Singular Value Decomposition (SVD)**.  
It demonstrates how to embed and extract one or more watermarks from images while preserving image quality.

---

## ✨ Key Contents

### Notebook
- **`watermark.ipynb`**  
  - Image loading & visualization  
  - **Watermark embedding** using SVD decomposition  
  - **Watermark extraction** from distorted images  
  - Extension: embedding and extracting **two watermarks simultaneously**  
  - Mathematical explanations with formulas for embedding and extraction steps  
  - Reference section with academic sources on SVD-based watermarking  

### Images (`images/` folder)
- `dog.jpg`, `dog.png`, `1.jpeg` → Base images for watermarking  
- `watermark1.jpeg`, `watermark2.jpeg` → Sample watermarks  
- `extract_watermarked_image.png`, `path_to_save_watermarked_image.png` → Example outputs from experiments  

---

## 🧱 Project Structure
```
SVD-Based-Image-Watermarking-main/
├── watermark.ipynb   # Main notebook implementing watermarking & extraction
└── images/           # Input images, watermarks, and output examples
```

---

## 🎯 Research Context
This project was developed as part of a **study on digital watermarking techniques**.  
It demonstrates how **linear algebra (SVD)** can be applied to secure image watermarking, ensuring both **imperceptibility** and **capacity**.

---

📚 Made for research & learning — blending math, image processing, and code.
