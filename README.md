# Project definition
Weather Prediction Using Deep Learning Techniques


<img src="https://github.com/yashthesia/weatherDL/blob/master/weather.gif" width="1000" height="500" />


# Presented by
15BCE120 – Meera Suthar
15BCE126 – Yash Thesia
15BCE130 – Vidhey Oza


# Abstract

Accurate weather prediction is a critical challenge with significant societal and economic impact, especially given the exponential growth of meteorological data from satellites and ground-based sensors. This paper surveys state-of-the-art deep learning approaches for weather forecasting, focusing on spatio-temporal data and time-series analysis. We review the application of Convolutional Neural Networks (CNNs) for spatial feature extraction, Recurrent Neural Networks (RNNs) and Long Short-Term Memory (LSTM) networks for temporal modeling, and autoencoders for robust feature learning and dimensionality reduction. The survey highlights the effectiveness of dynamic convolutional layers for short-range prediction, ConvLSTM architectures for integrating spatial and temporal dependencies, and stacked denoising autoencoders for mitigating overfitting and improving generalization. We discuss data preprocessing challenges, including handling missing values, normalization, and the integration of simulated and real-world datasets. Our analysis demonstrates that deep learning models, particularly those combining convolutional and recurrent architectures, significantly outperform traditional statistical methods in precipitation and extreme weather forecasting. We conclude by outlining future research directions, such as multi-modal data fusion and advanced spatio-temporal modeling, to further enhance predictive accuracy and reliability in operational meteorology.


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

