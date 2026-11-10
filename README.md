# Image Binarization Results

This repository contains **only the results** of applying four binarization algorithms to a test image dataset. No source code is included.

## Algorithms Used
The folders present the processing results of the following methods:
1. **Classic global Otsu's method**
2. **Unbalanced modification of Otsu's criterion** (for cases where *a priori* class weights of the object and background are not equal)
3. **Local Niblack's algorithm** (threshold function \(T(x,y) = \mu(x,y) + \alpha \sigma(x,y)\))
4. **Multi-scale modification of Niblack's algorithm** (proposed by V. Postnikov)

## Dataset
The processing was performed on a test set of **20 diverse grayscale images**. 

*Note:* Full-color (multi-channel) images were intentionally not processed.

# Binarization
![изображение](results/0.jpg)
![изображение](results/1.jpg)
![изображение](results/2.JPG.jpg)
![изображение](results/3.jpg)
![изображение](results/5.bmp.jpg)
![изображение](results/6.jpg)
![изображение](results/7.bmp.jpg)
![изображение](results/8.jpg)
![изображение](results/10.jpg)
![изображение](results/12.jpg)
![изображение](results/13.jpg.jpg)
![изображение](results/16.jpg)
![изображение](results/17.jpg.jpg)
![изображение](results/18.jpg.jpg)
![изображение](results/19.jpg.jpg)
![изображение](results/20.jpg.jpg)
![изображение](results/21.jpg)
![изображение](results/22.JPG.jpg)
![изображение](results/25.jpg)
