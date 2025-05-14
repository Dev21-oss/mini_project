# 🎨 Black and White Image Colorization using Deep Learning

This project implements an end-to-end deep learning pipeline to automatically colorize grayscale images using **Conditional Generative Adversarial Networks (cGANs)** with a **U-Net** architecture. An enhanced version with a **ResNet18 backbone** is also included for better color fidelity and realism.

## 📌 Overview

Black and white image colorization is a classic computer vision problem that aims to add plausible color to grayscale images. This project leverages the power of **cGANs** and **LAB color space** to generate photorealistic colorizations from black-and-white inputs — without any human hints or reference images.

## ✨ Features

- ✔️ Fully automatic image colorization
- 🧠 Conditional GAN architecture with U-Net generator
- ⚙️ Enhanced model with pretrained ResNet18 encoder
- 🖼️ Trained on COCO dataset (10,000+ images)
- 💡 LAB color space used to reduce complexity and improve results
- 📉 L1 loss + adversarial loss for stable and accurate learning
- 🔍 Works on legacy black-and-white photographs

## 🧠 Model Architecture
Generator: U-Net or ResNet18 + U-Net

Discriminator: PatchGAN

Loss: L1 Loss + Adversarial Loss

## 🧪 Results
✔️ Realistic and vivid colors with no artifacts or spillovers

✔️ Handles both natural and legacy grayscale images

✔️ 80% of users in a blind test believed generated images were real

## 🛠️ Technologies Used
Python

PyTorch

OpenCV

Google Colab (for training)

torchvision, matplotlib and many more different libraries

## 🙌 Acknowledgments
Based on the paper: “Black and White Image Colorization using Deep Learning”, IEEE 2022
