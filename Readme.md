The implementation is shared between three files - 

1. data_analysis.ipynb 

This file contains the following steps - 
- exploratory data analysis of the curves.csv and labels.csv.
- creating a unified dataset 
- plot to show amplitude vs time taken (inspired by plot1.png)
- creating a training dataset with known samples and test dataset with unknown samples
- basic feature engineering
- saving the bew datasets as csv files

2. modelling.ipynb
This file contains -
- implementation of technique 1 - to determine the time threshold (Cq).
In this implementation, there are two different methods - 1. determining time threshold (Cq) for a fixed signal threshold (100000) and 2. determining time threshodl (Cq) when the difference between signal thresholds is significantly high to reduce the margin of error. 
- implementation of technique 2 - using machine learning model
In this implementation, there are two different methods - 1. training and validation without feature engineering and 2. training and validation using new features

3. results_analysis.ipynb

This file contains -
- results from analyzing the signal thresholds using both techniques
- results from analyzing the classification models on the training datasets
- Conclusion of the study
- Further improvements
