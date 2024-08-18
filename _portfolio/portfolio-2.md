---
title: "Image Dehazing using DDPM"
excerpt: "Short description of portfolio item number 2 <br/><img src='/images/dehazing result.png'>"
collection: portfolio
---

Due to the presence of turbid mediums such as water droplets, particles, and sand, haze, smoke, or fog can obscure the scene and result in unclear images. The goal of image dehazing is to improve image clarity, not only to provide better visualization but also to enhance performance in object detection. This project is based on [DehazeDDPM](https://arxiv.org/abs/2308.11949). The model utilizes U-Net to extract features for the image formation model and then employs a diffusion model to restore the clear image. Additionally, we incorporate a 2D discrete wavelet module to extract new features and enhance the learning pipeline for improved results. The architecture is shown below:

![alt text](images/Architecture.jpg "arch")