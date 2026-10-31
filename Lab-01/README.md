# Lab 01 — Fundamentals of Computer Imaging

## 📌 Overview

This lab focuses on the fundamentals of computer imaging and practical image processing using Python, OpenCV, NumPy, and Matplotlib.

The objective is to understand how digital images can be read, transformed, analyzed, enhanced, and processed to extract meaningful visual information.

## 🎯 Learning Objectives

- Understand basic image representation and color channels.
- Perform fundamental image transformations.
- Analyze image quality using grayscale intensity statistics and histograms.
- Apply image enhancement techniques based on image quality issues.
- Extract Regions of Interest (ROIs) and crop unnecessary background areas.
- Build an image processing workflow using thresholding, segmentation, and pixel-level operations.

## 🛠️ Technologies & Libraries

- Python
- OpenCV (`cv2`)
- NumPy
- Matplotlib
- Google Colab
- Jupyter Notebook

## 📚 Concepts & Practical Work

### 1. Core Image Processing Operations

Practiced fundamental operations, including:

- Reading and displaying images
- BGR to RGB color conversion
- Grayscale conversion
- Image rotation and resizing
- Horizontal and vertical flipping
- Center cropping and ROI extraction
- Color channel extraction
- Binary thresholding
- Gaussian blurring
- Canny edge detection
- Brightness and contrast adjustment
- Negative transformation
- Drawing shapes and zooming
- Pixel-level operations using NumPy

### 2. Image Quality Analysis & Enhancement

Developed an image analysis workflow to identify common image quality issues:

- Over-dark images
- Over-bright images
- Low-contrast images
- Normal images

Explored grayscale histogram analysis and image intensity statistics to understand image quality.

Applied suitable enhancement techniques according to the identified issue, including:

- Negative transformation
- Power-law (gamma) transformation
- Logarithmic transformation
- Contrast stretching
- Histogram equalization

The enhancement method depends on the image characteristics and the problem being addressed.

### 3. Automatic Cropping & ROI Extraction

Worked on extracting meaningful image regions by:

- Identifying and cropping unnecessary plain background areas
- Extracting Regions of Interest (ROIs)
- Isolating individual regions for further processing

### 4. Image Processing Pipeline

Explored an image processing workflow involving:

1. Image reading
2. Grayscale conversion
3. Binary thresholding using Otsu's method
4. Splitting the image into regions
5. Cropping excess white background around objects
6. Extracting object borders using pixel-neighbor operations
7. Displaying intermediate and final results

Also explored morphological gradient using a 17 × 17 kernel.

## 🔬 Practical Tasks & Problem Solving

The lab included practical exercises and problem-solving tasks involving:

- Extracting the blue color channel
- Applying horizontal and vertical flips
- Performing center cropping
- Reducing image size through pixel skipping
- Rotating images by 180 degrees
- Automatically cropping objects from plain backgrounds
- Extracting multiple ROIs
- Identifying binary, grayscale, and RGB images
- Diagnosing image quality using histogram analysis
- Applying image enhancement techniques
- Processing image regions and extracting object borders

## 🌍 Real-World Applications

The concepts explored in this lab can support various computer vision applications, such as:

- **Manufacturing:** Image preparation and visual quality inspection
- **Textile Industry:** Preparing images for fabric defect analysis
- **Smart Traffic Monitoring:** Image preprocessing before vehicle detection and analysis
- **Computer Vision Applications:** Preparing user-uploaded images for downstream processing

These are potential applications of the concepts, not claims of complete systems implemented in this lab.

## 💡 Key Learnings

- Digital images contain information that can be analyzed at the pixel level.
- Image quality can influence the results of downstream computer vision tasks.
- Brightness and contrast represent different image characteristics.
- ROI extraction helps focus processing on relevant image regions.
- Preprocessing methods should be selected according to the image and task.

## ▶️ How to Run

1. Open the notebook in Google Colab.
2. Upload or provide access to the required input images.
3. Update image paths according to your environment.
4. Install any missing dependencies if required.
5. Run the notebook cells in sequence.


## 📂 Lab Resources

- **Notebook:** `Lab_1.ipynb`
- **Instructions:** Original lab handout
- **Python Implementation:** `Lab_1.py`
- **Input Images:** Lab-specific image resources
- **Outputs:** Selected screenshots and processed results

## 🚀 Learning Journey

This lab marks the beginning of my journey into Computer Vision.

My biggest takeaway is that advanced Computer Vision starts with understanding the data itself. Learning how images work gives me a stronger foundation to explore more complex vision systems.

I look forward to moving beyond fundamental image processing and exploring advanced concepts, deep learning-based vision models, and practical computer vision applications.


*Part of my Computer Vision learning journey — documenting practical work and progress throughout the semester.*
