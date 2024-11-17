# Architectural-Document-Image-Cleaning-Evaluation

This repository provides tools for evaluating the cleaning process of architectural document images. It is designed to assess the effectiveness of image cleaning techniques applied to architectural document images.

This repository provides scripts to convert cleaned images into binary masks, compute essential evaluation metrics, and visualize both the results and performance through various plots.

When you're enhancing scanned architectural drawings, this tool offers a straightforward way to quantify and visualize the quality of your image cleaning processes.

# Features
**1. Binary Mask Generation:**

Converts grayscale images to binary masks using Otsu's thresholding for effective segmentation.

Supports document images with intricate patterns and varying lighting conditions.

**2. Metrics Calculation:**

**IoU**: Evaluates the overlap between the ground truth and predicted masks.

**Dice Coefficient**: Measures the similarity between the binary masks.

**Precision & Recall**: Computes pixel-level precision and recall to assess performance.

**AUC-PR**: Visualizes the trade-off between precision and recall using the precision-recall curve.

**3. Visualization:**

Side-by-side comparison of ground truth, binary masks, and cleaned outputs for easy evaluation.

Precision-Recall curve plotting for insightful performance analysis.

# Usage
**1. Prepare Input Images:**

Provide the ground truth (*.png) and the cleaned image (*_cleaned.png) of the same size.

**2. Run the Code:**

Computes metrics and visualizes results.

Requires libraries: Pillow, numpy, scikit-image, scikit-learn, and matplotlib.

**3. Output:**

Metrics (IoU, Dice, Precision, Recall, AUC-PR) printed in the console.

Visualization of masks and precision-recall curve.

# Dependencies

Pillow

numpy

scikit-image

scikit-learn

matplotlib

# Applications

**Document Image Processing**: Evaluate the effectiveness of pre-processing or cleaning algorithms.

**Image Segmentation**: Evaluate the performance of segmentation techniques for Architectural Drawings images.

![image](https://github.com/user-attachments/assets/4537f606-096c-4efd-8376-503ac54510f8)

![image](https://github.com/user-attachments/assets/ef160f66-5b8d-4910-bb03-b7719ba27195)



