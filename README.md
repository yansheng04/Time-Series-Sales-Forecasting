### **Time Series Sales Forecasting**



##### Project Overview



This project aims to forecast future sales using historical sales data. Two forecasting approaches were implemented and compared:



* Prophet
* Long Short-Term Memory (LSTM)



The models were evaluated using Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and Mean Absolute Percentage Error (MAPE).



##### Dataset



The dataset contains historical daily sales records with the following attributes:



* Date
* Store
* Item
* Sales



The objective is to analyze historical sales patterns and forecast future sales.



##### Approach



###### 1\. Data Preprocessing

* Loaded train.csv and test.csv datasets.
* Converted the date column into datetime format.
* Checked for missing values and data consistency.



###### 2\. Exploratory Data Analysis (EDA)

Several visualizations were created to understand sales patterns:



* Daily Sales Trend
* Monthly Sales Trend
* Store Sales Distribution



These visualizations helped identify seasonality and overall sales trends.



###### 3\. Feature Engineering

The following temporal features were extracted from the date column:



* Year
* Month
* Day
* Day of Week
* Week of Year



These features help capture seasonal and temporal sales behavior.



###### 4\. Prophet Forecasting Model

Prophet was used because it can automatically model trend and seasonality components while remaining interpretable and easy to implement.



###### 5\. LSTM Forecasting Model

LSTM was implemented as a deep learning approach capable of learning complex temporal dependencies from historical sales observations.



###### 6\. Model Evaluation

The following evaluation metrics were used:



* MAE (Mean Absolute Error)
* RMSE (Root Mean Squared Error)
* MAPE (Mean Absolute Percentage Error)



The forecasting performance of Prophet and LSTM was compared using these metrics.

##### 

##### Technologies and Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* Prophet
* TensorFlow / Keras
* Scikit-learn
* Google Colab



##### Results

Both Prophet and LSTM models were evaluated using MAE, RMSE, and MAPE. The model with the lower RMSE and MAPE was considered the better-performing forecasting model.



##### Steps to Reproduce the Results

1. Download or clone this repository.
2. Install the required Python libraries:
* pandas
* numpy
* matplotlib
* prophet
* tensorflow
* scikit-learn

3\. Open the notebook Intern\_Task.ipynb using Google Colab or Jupyter Notebook.

4\. Ensure the dataset files (train.csv, test.csv, and sample\_submission.csv) are available in the specified directory.

5\. Run all notebook cells from top to bottom.

6\. Review the generated visualizations, forecasting results, and model evaluation metrics.



