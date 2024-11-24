
# Autoencoder based Semantic Communication for images

## Abstract : 

This project implements and evaluates an autoencoder-based semantic communication system and compares it with the widely-used JPEG compression technique in terms of quality, efficiency, and transmission robustness.

## Introduction:

semantic communication emphasizes transmitting meaningful information rather than raw data. Autoencoders, a type of neural network, are employed to extract and compress critical semantic features from images. The goal is to maintain image integrity while reducing bandwidth requirements. JPEG, a traditional image compression technique, operates by reducing spatial redundancy using discrete cosine transform (DCT). 

## Methodology:

### Autoencoder Architecture

#### Encoder: Compresses input images into a latent feature representation.
#### Decoder: Reconstructs the image from the latent representation.
#### Loss Function: Mean Squared Error (MSE) ensures fidelity during reconstruction.
### JPEG Compression

#### Standard DCT-based compression.
Retains high-frequency and low-frequency components based on a quantization matrix.

## Evaluation Metrics

Peak Signal-to-Noise Ratio (PSNR): Measures image quality.

Structural Similarity Index (SSIM): Assesses perceptual quality.

Compression Ratio (CR): Indicates efficiency.



