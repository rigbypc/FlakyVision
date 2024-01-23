# FlakyVision
FlakyVision predicts the lifetime class of flaky tests with 73% precision. 

The original source of data is located in Data/log.txt. In order to replicate the result, follow these steps:
**Note: ** If you wish to just run the model on cleaned data, skip the first step and go straight to model folder.

1. Run **text_to_dataframe.ipynb** notebook in the preprocessing folder to convert the text file into a data frame saved in full_log_df.csv and also calculate the lifetime of tests and save it into Life_time_full_log.csv.

2. Run **Flaky Life Time Prediction using RF method.ipynb** 

