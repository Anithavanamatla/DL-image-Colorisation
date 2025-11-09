**Project Title:** *Automatic Image Colorization using Deep Learning*

This project presents an **automatic image colorization system** using **deep learning** to convert grayscale images into realistic color versions. Traditional colorization requires manual effort and artistic expertise, making it time-consuming and subjective. To address this, a **Convolutional Autoencoder model** based on **CNNs** is implemented to learn the mapping between luminance (L-channel) and chrominance (a, b channels) in the **LAB color space**.

The **Image Colorization Dataset** from **Kaggle** is used, containing paired grayscale and color images resized to **256×256 pixels** and normalized within **[0,1]**. The model is trained on an **80:20 split** of the data using the **Mean Squared Error (MSE)** loss function and **Adam optimizer** for stable convergence.

Performance is evaluated using **Structural Similarity Index (SSIM)** and **Peak Signal-to-Noise Ratio (PSNR)**, achieving an **average SSIM of 0.8768** and **PSNR of 22.84 dB**. These results indicate strong structural consistency and good reconstruction quality, proving the model’s effectiveness in generating natural and visually appealing colorized images.

Future improvements include integrating **GANs or Transformer models** for enhanced realism, and developing a **user-friendly interface** for real-time image and video colorization, extending applications to **historical photo restoration** and **digital media enhancement**.
