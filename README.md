# Energy Load Forecasting, by Ania Supady
Fourier series analysis and Fourier transform, Wavelet function.

---

link to colab: https://github.com/AniaSupady/Energy-Load-Forecasting/blob/main/Forecasting_Energy_Load.ipynb

----  


**Steps for Forecasting Energy Load using Wavelet and Fourier Transforms**:  

**Import Libraries:**  

Import necessary libraries such as pandas, numpy, and matplotlib for data manipulation and visualization.   

**Load Data:**   
Load the energy load data into the Jupyter Notebook.   

**Data Preprocessing:** 
Clean and preprocess the data by handling missing values, converting data types, and normalizing the data.   

**Wavelet Transform:**   

Apply the wavelet transform to the energy load data to decompose it into different frequency components.  
Use a suitable wavelet function (e.g., Haar, Daubechies) and decomposition level.   

**Fourier Transform:**  

Apply the Fourier transform to the wavelet-transformed data to further decompose it into frequency components.  
Use a suitable Fourier transform algorithm (e.g., Fast Fourier Transform).  

**Modeling Each Frequency Component:**  

Model each frequency component separately using an appropriate technique (e.g., ARIMA, Prophet).  
Fit the models to the historical data and evaluate their performance.  

**Reconstructing the Forecast:**   

Reconstruct the final forecast by aggregating the forecasts from each frequency component.  
Use the inverse wavelet transform to combine the forecasts from different frequency components.  

**Evaluate Model Performance:**  

Assess the accuracy of the final forecast using metrics like mean squared error or mean absolute error.  
Compare the performance of the wavelet-Fourier approach to other forecasting techniques.  
The Jupyter Notebook likely contains detailed code and examples demonstrating these steps. By following the steps outlined in the notebook, you can implement the wavelet-Fourier approach for forecasting energy load.  
