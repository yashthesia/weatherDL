# Project definition
Weather Prediction Using Deep Learning Techniques


<img src="https://github.com/yashthesia/weatherDL/blob/master/weather.gif" width="1000" height="500" />


# Presented by
15BCE120 – Meera Suthar
15BCE126 – Yash Thesia
15BCE130 – Vidhey Oza


# Abstract

Image data has become a crucial part of daily life. The image quality depends on parameters such as bad weather, electrical noise, poor lighting, camera quality, etc. The obvious solution here is to perform image preprocessing before feeding images to any network, but sometimes that leads us to noisy, blurry, color-shifted images. There has been significant progress in Convolution-based Deep Learning models in the Computer Vision domain which solve many challenging issues such as Image Denoising, Image Restoration, Image Segmentation, and Detection. While solving low-light image-related issues, a Convolutional model can give us promising results as we need to add the features while still maintaining image size and shape. We proposed an Attention U-Net GAN model architecture that makes use of supervised learning using the See-in-theDark (SID) dataset and enhances low light images. Attention U-Net is useful to highlight dark spots in the images and GAN learns high-level image enhancement loss automatically and produces a brighter image. We compared our results with other benchmark techniques and received improved peak signal-to-noise-ratio (PSNR) values.


# Libraries required
numpy, pandas, matplotlib, tensorflow, keras, scikit-learn, their dependencies, and other built-in libraries.

# Files/directories in package 

WeatherDL – contains python scripts.
1. model_maker.py – contains different implementations as discussed in term paper. 
2. data_maker.py – data formatting python scripts (in format required by model_maker.py). 
3. sample.py – RUN THIS FILE. 

dataset – contains date-wise CSV data for different locations. Obtained from Dr. Sanjay Garg as part of Minor Project with Vidhey Oza & Dhananjay Rasalia

weather.gif – animation of heatmaps of meteorological variables over a 50-day time period. 


*Please refer to inline comments in python scripts for detailed descriptions.*

*Please change paths in data_maker.py, as complete paths may have to be given for the code to run properly.*

