# GAN-for-CVD
This repository aims to use a color compensation algorithm and a GAN to recolor problematic colors for those with color vision deficiency (CVD). For the algorithmic approach, the paper [Naturalness Preserving Image Recoloring Algorithm - Hassan, Paramesran](https://www.sciencedirect.com/science/article/abs/pii/S0923596517300954) was referred to. 

## Method

Two separate approaches were taken in order to recolor the images.
1. Algorithmic- It is ensured that the luminance and hue of the input and output images is the same in order to maintain the naturalness of the image. 
2. GAN- A generator and discriminator based model is used to recolor the images through 50 epochs.

## Results

### Algorithm

[Original 1](https://github.com/NBhavithaReddy/GAN-for-CVD/tree/main/outputs/image73.jpg)
[Recolored 1](https://github.com/NBhavithaReddy/GAN-for-CVD/tree/main/outputs/file_image73.jpg_.jpeg)

[Original 2](https://github.com/NBhavithaReddy/GAN-for-CVD/tree/main/outputs/image84.jpg)
[Recolored 2](https://github.com/NBhavithaReddy/GAN-for-CVD/tree/main/outputs/file_image84.jpg_.jpeg)

[Original 3](https://github.com/NBhavithaReddy/GAN-for-CVD/tree/main/outputs/image99.jpg)
[Recolored 3](https://github.com/NBhavithaReddy/GAN-for-CVD/tree/main/outputs/file_image99.jpg_.jpeg)


### GAN 

[Result 1](https://github.com/NBhavithaReddy/GAN-for-CVD/tree/main/outputs/Screenshot (65).png) <br>
[Result 2](https://github.com/NBhavithaReddy/GAN-for-CVD/tree/main/outputs/Screenshot (66).png)
