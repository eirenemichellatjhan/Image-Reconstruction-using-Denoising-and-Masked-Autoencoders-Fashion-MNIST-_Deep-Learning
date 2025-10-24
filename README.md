# Image-Reconstruction-using-Denoising-and-Masked-Autoencoders-Fashion-MNIST-_Deep-Learning

Image Reconstruction using Denoising and Masked Autoencoders (Fashion MNIST) | Link
This project explores how autoencoders can learn efficient visual representations for grayscale fashion images. Using the Fashion MNIST dataset, both Denoising Autoencoder (DAE) and Masked Autoencoder (MAE) models were developed to reconstruct images from incomplete or noisy inputs, demonstrating the ability of deep learning models to capture meaningful structure in limited data.

**Tools**: Python, TensorFlow, Keras, NumPy, Matplotlib

**Approach**: Implemented and trained both DAE and MAE architectures for 100 epochs. The DAE learned to remove Gaussian noise from images, while the MAE reconstructed masked image patches, focusing on structure-level understanding.

**Results**: The DAE achieved an average SSIM of 0.61 (best 0.96), indicating good reconstruction quality despite occasional failure on complex textures. The MAE produced low and stable loss, maintaining high SSIM on most samples and showing strong structural consistency even with partial visual input.

**Key Insight**: The DAE excelled in pixel-level recovery, while the MAE proved better at learning robust visual representations, showing that self-supervised approaches can perform well even with incomplete data.
