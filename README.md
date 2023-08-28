# Kernel-density-estimation-using-Parzen-window-method
Kernel density estimation using Parzen window algorithm using different window lenghts.

This GitHub repository presents an exploration of the Parzen Window method for density estimation. The method involves windowing data points to estimate the underlying probability density function. This README provides an overview of the concept and the results obtained from applying the Parzen Window method to the dataset.

As observed, increasing the window length results in smoother estimations. In other words, a larger window leads to lower variance and higher bias in the data. Conversely, a smaller window focuses on nearby data points, leading to higher variance and lower bias, and potentially leading to overfitting.
Using the built-in MATLAB functions and the Parzen Window technique, the distribution of data can be visualized efficiently. This is achieved by applying the Parzen window with appropriate window sizes.
Through the Parzen Window approach, the distribution of the data can be estimated and visualized. The resulting distribution provides insights into the underlying patterns and variations in the data.
![image](https://github.com/romidi80/Kernel-density-estimation-using-Parzen-window-method/assets/89667194/d6f1d272-45bf-4438-9ccf-c635cce8fdce)


## Impact of Window Size
The choice of the Parzen window size significantly impacts the density estimation. Smaller window sizes result in highly variable density estimations, while larger window sizes yield smoother but potentially biased estimations.

## Overfitting Phenomenon
As evident from the observations, using very small Parzen window sizes can lead to overfitting. The model becomes excessively sensitive to minor variations in the data, causing a high degree of variance and, consequently, overfitting.
