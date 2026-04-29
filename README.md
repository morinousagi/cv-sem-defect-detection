# SEM Images Defect Detection

A minimal demo app was deployed to [GitHub Page](https://morinousagi.github.io/cv-sem-defect-detection).

## Dataset

- Source & Citation: Cheng, Deruo, 2021, "MIIC (Microscopic Images of Integrated Circuits) Dataset for Anomaly Detection and Image Inpainting", https://doi.org/10.21979/N9/WBLTFI, DR-NTU (Data), V1. The data accompanies the publication: "Joint Anomaly Detection and Inpainting for Microscopy Images via Deep Self-Supervised Learning", IEEE International Conference on Image Processing (ICIP), 2021.
- 512x512 grayscale (1 channel) images, largely metal interconnects images.

## Model Training

- The model was created and exported using [Teachable Machine](https://teachablemachine.withgoogle.com).
- Only 100 normal and 116 anomaly images were used in machine learning - just to have fun with Teachable Machine.
- Epochs: 50
- Batch Size: 16
- Learning rate: 0.0001

---
<img width="556" height="465" alt="image" src="https://github.com/user-attachments/assets/c5acc825-36e4-4971-93ca-cb7eb7428a91" />

---
<img width="574" height="465" alt="image" src="https://github.com/user-attachments/assets/bda122a7-a7d5-4df7-9647-52f8cec07ab8" />

---
<img width="453" height="188" alt="image" src="https://github.com/user-attachments/assets/7ee6151e-58cc-44fb-9d40-5be5d88e458b" />

---
<img width="537" height="433" alt="image" src="https://github.com/user-attachments/assets/ab17ab8f-c472-4d38-897b-2f63c0f2f44c" />


