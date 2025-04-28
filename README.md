# Image Segmentation with U-Net

This project implements an image segmentation pipeline using a U-Net architecture to segment road features from images captured by a car-mounted camera.  
It is part of **Week 3 (Course 4: Convolutional Neural Networks)** from the **Deep Learning Specialization** by **Andrew Ng** on Coursera.

---

## Description

In this assignment, the U-Net model is trained to perform pixel-wise classification to identify drivable road areas from vehicle-mounted camera images.  
The project includes:

- Preprocessing input images and masks
- Building and training a U-Net model from scratch
- Predicting segmentation masks on new input images
- Visualizing segmentation outputs and ground truth comparisons

---

## Important Note

Due to file size limitations, the full dataset has been removed from this repository.  
If you want to reproduce the results:

- Download the original dataset separately as instructed in the notebook (`Image_segmentation_Unet_v2.ipynb`).
- Place the dataset inside a `data/` directory following the expected structure (`data/CameraRGB/` and `data/CameraMask/`).

---

## Files and Folders Included

- `Image_segmentation_Unet_v2.ipynb` — Main Jupyter notebook for model training and evaluation
- `outputs.py` — Helper functions for visualization
- `test_utils.py` — Helper functions for evaluation
- `images/` — Sample images for demonstration
- `LICENSE` — License file

---

## Key Concepts Covered

- U-Net architecture for semantic segmentation
- Encoder-decoder structures with skip connections
- Image preprocessing and augmentation
- Loss functions for segmentation (cross-entropy)
- Evaluation of segmentation models

---

## Course Information

This project is part of:  
[Deep Learning Specialization](https://www.coursera.org/specializations/deep-learning)  
Instructor: **Andrew Ng**  
Course 4: **Convolutional Neural Networks**  
Week 3: **Image Segmentation with U-Net**

---

## License

This repository is created for educational and portfolio purposes only.  
It should not be used for direct assignment submission.

---
