# DS9000-FlightDelayPrediction

## Data set
We coulddn't upload the dataset on github due to size limit but we have attached the link to it down below. You can reporduce the dataset used by following the data preprocessing steps we followed.
https://www.kaggle.com/datasets/robikscube/flight-delay-dataset-20182022/data

## Data Preprocessing
1. We converted the data into smaller datatypes in the EDA part and removed the unnecessary column. All the steps are clearly defined in the EDA file.
2. Although, when we loaded in the dataset for the modelling part, we realized it got corrupted due to pandas to_parquet method not supporting float16. We went back to the EDA file and converted those column to int16 for better support and efficiency. This step was performed at the end of the EDA file and we have mentioned it so there.
3. Then we imported the new dataset file and performed some more preprocessing for the modelling. Everything is well documented in the jupyter file as well.
4. After all the preprocessing, now the dataset is ready to be used for performing machine learning.
