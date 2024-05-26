
# Image Compression using PCA

This section focuses on using Principal Component Analysis (PCA) implemented from scract using Numpy for image compression and reconstruction.

## Directory Structure

```
Image-Compression-PCA/
├── Image_Compression_PCA.ipynb
├── PCA_Image.jpeg
└── README.md
```

## Tasks

1. **RGB Channel Splitting and Normalization:** Split the image into R, G, B channels and normalize.
2. **Covariance Calculation:** Calculate the covariance matrix for each channel.
3. **Eigen Decomposition:** Perform eigen decomposition to obtain eigenvalues and eigenvectors.
4. **Image Compression:** Reduce the dimensions of the image using PCA and reconstruct it.
5. **Variance Explained Plot:** Plot the cumulative variance explained by the principal components.

## Requirements

- numpy
- matplotlib

## How to Run

1. Install the required packages:
```bash
pip install <requirements>
```
Run the Jupyter Notebook:
```bash
jupyter notebook Image_Compression_PCA.ipynb
```