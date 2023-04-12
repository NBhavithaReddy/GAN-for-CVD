# GAN-for-CVD
This repository aims to use a color compensation algorithm and a GAN to recolor problematic colors for those with color vision deficiency (CVD). For the algorithmic approach, the paper [Naturalness Preserving Image Recoloring Algorithm - Hassan, Paramesran](https://www.sciencedirect.com/science/article/abs/pii/S0923596517300954) was referred to. 

## Method

Two separate approaches were taken in order to recolor the images.
1. Algorithmic- It is ensured that the luminance and hue of the input and output images is the same in order to maintain the naturalness of the image. 
2. GAN- A generator and discriminator based model is used to recolor the images through 50 epochs.

## Results

