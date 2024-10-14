# pca-autoencoder-denoising
1) Description:
   This project focuses on denoising CIFAR-10 images using two approaches: Principal Component Analysis (PCA) and a custom-built autoencoder.
   The aim is to evaluate their effectiveness in noise reduction and data compression.

3) Key Features:
  Dataset Utilization: Utilizes the CIFAR-10 dataset, consisting of 60,000 32x32 color images in 10 classes, for training and testing purposes.
  Data Preprocessing: Normalizes image pixel values to the range [0, 1] and adds Gaussian noise (mean=0, stddev=0.2) to create noisy input images.
  Dimensionality Reduction with PCA: Applies PCA with 128 components for noise reduction and image reconstruction, achieving a compression ratio of 95.83%.
  Autoencoder Implementation: Constructs a deep learning autoencoder with dense layers to denoise the images, resulting in a significantly higher compression ratio of 99.87%.
  Visual Comparison: Displays original, noisy, and denoised images side by side for both methods, allowing subjective evaluation of denoising effectiveness.

4) Programming Tools:
    Python, NumPy, TensorFlow, Matplotlib, Scikit-learn
