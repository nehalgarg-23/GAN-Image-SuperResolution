# GAN-Image-SuperResolution
This repo implements an image super-resolution model using Generative Adversarial Networks (GANs). It enhances low-resolution images by training a deep learning model with a generator-discriminator architecture, improving image details and quality.


Data Preprocessing:

Loads low-resolution and high-resolution image pairs.

Performs image normalization and augmentation.


Model Architecture:

Implements an autoencoder-based generator.

Defines a discriminator for adversarial training.

Uses a combination of adversarial loss and perceptual loss.


Training Process:

Trains the GAN model on paired image datasets.

Evaluates training progress with loss functions and visual results.


Testing and Evaluation:

Applies the trained model to low-resolution images.

Computes metrics such as PSNR (Peak Signal-to-Noise Ratio) and SSIM (Structural Similarity Index) to measure performance.

Visualization:

Displays comparisons between low-resolution, generated high-resolution, and ground truth images.

