Data Question 6: Healthcare Bluebook

Goal : To determine which hospitals or facilities the patients are referred the most.

Preprocessing:
Different datasets containing hospital information, physician information and the medical specialization field were merged to perform the analysis
Since the datasets were huge, some of the datasets were read into SQL and only the necessary observations or fields were extracted and read into python.
Dask was used to import the dataset and Pickle used to save the data frame after processing, 

Tools used: Python and data visualization tool seaborn
