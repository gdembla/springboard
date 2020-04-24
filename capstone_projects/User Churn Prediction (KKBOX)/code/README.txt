The entire code for this project has been organized into the following python notebooks.

1) "Data Wrangling.ipynb" comprises of sample data extraction, data quality assessment, data cleaning, data manipulation and feature engineering (which uses feedback from Exploratory Data Analysis).
2) "Exploratory Data Analysis.ipynb" explores each of the available dataset from various angles and provides insights into potential feature set for model training.
3) "Model Building.ipynb" deals with training, tuning and evaluation of multiple statistical models.

The first notebook requires heavy computational power due to data sampling, aggregation and manipulation of millions of usage records, and hence, takes few hours to get through (4-5 hours on Intel i7 2.0GHz, 16GB RAM, 64-bit Windows 10 OS, 256GB solid-state drive).
Hence, in order to run the first notebook, you need comparable or better computational power along with free hard-disk space of atleast 50GB to store original raw data files. 
Raw data files need to be downloaded from Kaggle (https://www.kaggle.com/c/kkbox-churn-prediction-challenge/data), unzipped into csv files and placed in the directory "data/download" before the code can be run successfully.

If you want to skip the first notebook and run only second and third notebooks, then all the required massaged datasets are already available in the "data" directory.