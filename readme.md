## Sea Level Rise Prediction Using LiDAR and Machine Learning

This project uses elevation data from Light Detection and Ranging (LiDAR) to develop a short-term Sea Level Rise (SLR) forecast model and show the effects of it on the population and assets. Various climatic factors that impact sea level like the temperature, precipitation was identified and collected along with LiDAR data making this a multivariate time series forecast machine learning problem. The models proposed are Convolutional Neural Networks (CNN-LSTM), Adaptive Neuro-Fuzzy Inference System (ANFIS), Multi-Layer Perceptron (MLP) to predict SLR and Vector Auto Regression (VAR), Multiple linear regression (MLR) to estimate the corresponding asset loss. The models are evaluated using R2 score, Root Mean Square Error (RMSE), Mean Absolute Percentage Error (MAPE). Based on the comparative analysis, CNN-LSTM with RMSE of 0.133 and R2 of 98%, MLR with RMSE of 0.04 and R2 of 99% were identified as the best models for SLR prediction and Asset loss estimation respectively. A web portal was designed to view the future SLR, Asset and population loss. The project can be scaled to cover more coastal regions to help governments take preventive measures and mitigate the loss of population and valuable assets. 

## Project Architechture:

<img width="576" alt="image" src="https://user-images.githubusercontent.com/49642360/208184413-c521503b-4b8a-48b6-aad8-08535987a920.png">



## Data Sources:


<img width="1287" alt="Screen Shot 2022-12-16 at 12 34 42 PM" src="https://user-images.githubusercontent.com/49642360/208184543-e749aa16-4d34-40cf-b68c-aa984eecfd28.png">




## LiDAR Data Pre-Processing:

<img width="1331" alt="Screen Shot 2022-12-16 at 12 35 28 PM" src="https://user-images.githubusercontent.com/49642360/208184783-a1964f42-108d-4b3a-a7b0-33a5f1e3fadd.png">




## Other Meteorological Factors Preprocessing :

<img width="1335" alt="Screen Shot 2022-12-16 at 12 35 41 PM" src="https://user-images.githubusercontent.com/49642360/208184890-a437942f-6279-4c3c-9dbe-ba1b176b2417.png">


## Final Predictions:



<img width="1375" alt="Screen Shot 2022-12-16 at 12 36 05 PM" src="https://user-images.githubusercontent.com/49642360/208184916-c83ae2c0-12fb-4c21-bdb2-7fa7ae704c5e.png">
