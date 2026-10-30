# Image Processing with Python – Assignment 3

## About the Project

This repository contains my **Image Processing Practical Assignment 3**, completed as part of the PGDM in Big Data Analytics.

The assignment focuses on applying Python-based image processing techniques to solve practical problems involving edge detection, image compression, noise removal, texture analysis, and image segmentation.

The practical implementations are performed using Jupyter Notebook and Python libraries.

## Practical Experiments

This assignment covers the following six problems:

### 1. Comparative Edge Detection on Natural Images
- Applied Sobel, Laplacian, and Canny edge detection techniques.
- Compared the results to understand how different operators identify edges in natural images.

### 2. Noise Sensitivity Experiment
- Added Gaussian noise and Salt-and-Pepper noise to images.
- Applied Sobel and Laplacian edge detection.
- Studied the impact of noise and the effectiveness of Gaussian blur.

### 3. Compression Ratio Comparison (RLE vs Huffman)
- Implemented Run-Length Encoding (RLE) and Huffman Coding.
- Compared compression performance and percentage size reduction.
- Studied how image characteristics affect compression efficiency.

### 4. JPEG Block Artifact Analysis
- Implemented JPEG-style compression using Discrete Cosine Transform (DCT) and quantisation.
- Compared low, medium, and high quantisation levels.
- Analysed image distortion using PSNR and SSIM.

### 5. Texture-Based Segmentation using GLCM Features
- Extracted texture features using Gray-Level Co-occurrence Matrix (GLCM).
- Analysed contrast, energy, and homogeneity.
- Applied K-Means clustering to segment images into different texture groups.

### 6. Multi-Feature Segmentation for Disease Detection
- Combined image intensity, Sobel gradient magnitude, and local texture variance.
- Applied K-Means clustering for image segmentation.
- Explored how multiple image features help distinguish different regions.

## Technologies and Libraries Used

- **Python** – Programming language
- **Jupyter Notebook** – Development environment
- **OpenCV (cv2)** – Image processing and edge detection
- **NumPy** – Numerical computations
- **Matplotlib** – Image visualisation
- **Scikit-image** – Texture analysis and image quality metrics
- **Scikit-learn** – K-Means clustering

## Project Structure

```text
Image-Processing-Assignment-3/
│
├── Swasti_BDA_ASS_3.ipynb
├── city.jpeg
├── clean.jpeg
├── leaf.jpg
├── outdoor.jpeg
├── smooth.png
└── texture.jpg
```

## Installation and Execution

1. Clone or download this repository.
2. Install the required Python libraries:

```bash
pip install numpy matplotlib opencv-python scikit-image scikit-learn
```

3. Open Jupyter Notebook:

```bash
jupyter notebook
```

4. Open `Swasti_BDA_ASS_3.ipynb`.
5. Run the notebook cells sequentially to execute the practical experiments.

## Key Learning Outcomes

Through this assignment, I explored:

- Different edge detection techniques and their applications.
- The effect of noise on image quality and edge detection.
- Lossless compression techniques and compression efficiency.
- JPEG compression using DCT and quantisation.
- Texture feature extraction using GLCM.
- Image segmentation using K-Means clustering.
- Image quality evaluation using PSNR and SSIM.

## Author

**Swasti Agrawal**

PGDM – Big Data Analytics (BDA)

---

*This repository is part of my academic practical work in Image Processing and Python.*
