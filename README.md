# US_Accident_Severity_Prediction_Model_v1

Logistic Regression model developed as part of The Coding School's *Introduction to AI* Capstone Project.  
The model predicts whether a traffic accident will be severe or not using 36,000+ crash records from the Chicago Police Department.

## Project Overview
- **Goal:** Build a supervised ML model to predict accident severity for traffic safety insights.  
- **Model:** Logistic Regression  
- **Dataset:** [Traffic Crashes - Crashes](https://data.cityofchicago.org/) (City of Chicago, Police Department crash reporting system)  
- **Size:** ~36k records (after preprocessing)  
- **Performance:**  
  - Overall accuracy: **90%+**  
  - Negative prediction rate (correctly identifying non-severe crashes): **92%+**

## Key Features
- Data cleaning and preprocessing (handling nulls, selecting relevant features)  
- Feature engineering from categorical & numerical crash attributes  
- Logistic Regression training pipeline with scikit-learn  
- Evaluation with accuracy, precision, recall, and confusion matrix  
- Insights into feature importance influencing accident severity  

## Results
While not perfect, the model successfully captured patterns in crash severity, achieving strong predictive performance.  
It highlighted correlations between accident severity and factors such as **road conditions, weather, and time of day**.  

## Links
- 📄 Detailed write-up and documented ML pipeline: [Medium Article](https://medium.com/@dersu13/predicting-if-a-traffic-accident-is-severe-using-logistic-regression-1b1da0bed4bd)  
- 📊 Dataset source: [Traffic Crashes - Crashes](https://data.cityofchicago.org/)  

## Tech Stack
- Python  
- Pandas / NumPy  
- scikit-learn  
- Matplotlib / Seaborn  

## How to Run/Reproduce Results
1. Open the Jupyter Notebook in Google Colab:  
   [US_Accident_Severity_Prediction_Model.ipynb](./US_Accident_Severity_Prediction_Model.ipynb)  

2. Download the dataset from the City of Chicago portal:  
   ["Traffic Crashes - Crashes"](https://data.cityofchicago.org/)  

3. Upload the dataset to your Google Drive and mount it in Colab.  

4. Run all cells in the notebook to reproduce the results. 
