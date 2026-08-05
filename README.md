# Generative Modelling Case Study

## Student
Dharanidhar Beere

## Overview
This project implements Generative Adversarial Networks (GANs) using PyTorch for different applications, including synthetic data generation, medical imaging, cybersecurity, and creative AI.

---

## Part 1: GANs from Scratch

### Sine-Wave GAN
- Trained a GAN to learn a sine-wave distribution.
- Compared real and generated samples.

### Mixture of Gaussians GAN
- Trained a GAN on a mixture of Gaussian clusters.
- Compared real and generated distributions.

### Architecture Modification
- Modified the network architecture.
- Compared results with the original GAN.

---

## Part 2: Real-World Applications

### Part 2.1 – OCTMNIST Retinal Images
- Built a DCGAN for retinal image generation.
- Generated synthetic OCT images.
- Evaluated results using FID score.

### Part 2.2 – CICIDS2017 Cybersecurity Data
- Built a GAN for network traffic generation.
- Generated synthetic traffic samples.
- Evaluated results using PCA and Mean Feature Difference.

### Part 2.3 – QuickDraw Birthday Cake Sketches
- Built a DCGAN for sketch generation.
- Generated synthetic birthday cake images.
- Compared generated and real sketches.

---

## Technologies Used

- Python
- PyTorch
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- MedMNIST
- KaggleHub

---

## How to Run

Install required packages:

```bash
pip install torch torchvision numpy pandas matplotlib scikit-learn medmnist kagglehub
```

Run the notebooks in order:

1. Part 1 – Sine Wave GAN
2. Part 1 – Mixture of Gaussians GAN
3. Part 2.1 – OCTMNIST DCGAN
4. Part 2.2 – CICIDS2017 GAN
5. Part 2.3 – QuickDraw DCGAN

---

## Author

Dharanidhar Beere

MSc Data Science with Advanced Research

University of Hertfordshire
