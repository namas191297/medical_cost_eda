# Medical Cost Analysis

This repository shows a detailed EDA of a data set consisting of the cost of treatment of different patients. The cost of treatment depends on many factors such as the type of clinic, diagnosis, region, gender etc. 

This Medical Cost dataset can be useful in analysing the different features and their correlation that affects the cost and expenses and can be used to extract/find useful features that can be used in estimating expenses.  

## Data

The dataset is available on GitHub: https://github.com/stedy/Machine-Learning-with-R-datasets

 ### Columns 

age: age of primary beneficiary

sex: insurance contractor gender, female, male

bmi: Body mass index, providing an understanding of body, weights that are relatively high or low relative to height, objective index of body weight (kg / m ^ 2) using the ratio of height to weight, ideally 18.5 to 24.9

children: Number of children covered by health insurance / Number of dependents

smoker: Smoking

region: the beneficiary's residential area in the US, northeast, southeast, southwest, northwest.

charges: Individual medical costs billed by health insurance

## Pre-processing

The dataset doesn't require a lot of pre-processing, however it does require converting the categorical data to nominal data in order to visualize better and find correlations between the features. Certain features such as smoker, sex and region have been converted to nominal data for better analysis.



## License
[MIT](https://choosealicense.com/licenses/mit/)
