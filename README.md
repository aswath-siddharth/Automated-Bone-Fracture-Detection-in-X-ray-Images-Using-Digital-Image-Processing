**Automated Bone Fracture Detection in X-ray Images Using Digital Image Processing**

This repository contains all materials related to our project “Automated Bone Fracture Detection in X-ray Images Using Digital Image Processing.”
The project uses classical Digital Image Processing (DIP) techniques along with a lightweight learning-based classifier to detect fractures in musculoskeletal X-ray images.

**The repository includes:**

The Jupyter Notebook containing the full implementation

The Project Report (PDF + DOCX)

The Presentation Slides (PPTX)

Files in This Repository
/bone-fracture-detection.ipynb        → Full code implementation
/Group17_Automated_Bone_Fracture_Detection_PPT.pptx   → Presentation
/Group17_Automated_Bone_Fracture_Detection_Report_PDF.pdf → Final report (PDF)
/Group17_Automated_Bone_Fracture_Detection_Report_Softcopy.docx → Report (DOCX)

**Project Summary
**
This project presents a DIP-based automated system for detecting bone fractures in X-ray images.
The approach focuses on explainability, lightweight processing, and high fracture visibility through image enhancement techniques.

**Workflow Overview (From Notebook & Report)**

**1)Preprocessing**
    * Resizing & normalization
    * Noise reduction using Gaussian and median filters

**2)Contrast Enhancement**
    * Linear contrast stretching
    * CLAHE for improved visibility

**3)Edge Detection**
     * Canny edge detector
     * Gradient magnitude & direction mapping

**4)Morphological Processing**
    * Dilation
    * Erosion
    * Closing to fix broken edges

**5)Segmentation**
    * Adaptive thresholding to isolate fracture regions
    
**6)Classification**
    **A lightweight CNN model classifies images as:**
        * Fractured
        * Non-fractured

Performance Summary

From the report:

**Metric	      Value**
Accuracy	    90.3%
Precision	    88.6%
Recall	      91.2%
F1-Score	    89.8%

**Dataset used: MURA (Musculoskeletal Radiographs).**
**
How to Run the Notebook**

**Install required packages:**

pip install opencv-python numpy matplotlib tensorflow scikit-learn


**Open the notebook:
**
jupyter notebook bone-fracture-detection.ipynb

**Technologies Used**
Python
OpenCV
NumPy
Matplotlib
TensorFlow / Keras
Jupyter Notebook




        
