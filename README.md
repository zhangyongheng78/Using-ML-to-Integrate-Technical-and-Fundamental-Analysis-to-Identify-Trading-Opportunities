# Stats170B Project

### (I) - Project Title: 
Using Machine Learning Techniques to Integrate Technical and Fundamental Analysis to Identify Trading Opportunities


### (II) - Student Names: 
Longxiang Dai, 70961656, longxiad@uci.edu

Yongheng Zhang, 42664320, yonghenz@uci.edu


### (III) - Our Dataset:
#### Clustering Dataset:
##### 1-Time Series DTW Sample.csv
Records the clutser numbers of the time-series data based on K-means and Dynamic Time Wraping distance
##### 2-Time Series Euclidean Sample.csv
Records the clutser numbers of the time-series data based on K-means and Dynamic Time Wraping distance


#### Training Dataset:
##### 1- Merged Daily Data Sample.csv
The dataset that we use for short-term prediction.
##### 2- Merged Quarterly Data Sample.csv
The dataset that we use for long-term prediction.


### (IV) - Our Notebook:
##### 1- get_data.ipynb
The notebook includes helpful functions to generate quarterly and daily features from SimFin and FRED datasets.
##### 2- Data Preprocessing.ipynb
Run the notebook to generate quarterly and daily and save the data into two csv files: merged quarterly data.csv, merged daily data.csv
##### 3- QOQ Prediction.ipynb
Train models to make quarter over quarter (QOQ) predictions. To run the notebook using the sample data, you'll need to change the corresponding file path to the sample data.
##### 4- WOW Prediction.ipynb
Train modesl to make week over week (WOW) predictions. To run the notebook using the sample data, you'll need to change the corresponding file path to the sample data.
