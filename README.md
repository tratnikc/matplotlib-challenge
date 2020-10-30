# matplotlib-challenge
 
## included:
1. mouse_metadata.csv in the data folder
2. Study_results.csv in the data folder
3. pymaceuticals.ipynb file, observations at the top of the notebook and at the bottom of this readme
4. this README.md file

## Requirements
Using the data provided on the 249 mice included in the study of several drug regimens to treat skin cancer, generate tables and figures needed for the technical report on the study. From these tables and figures, arrive at the high level summary of the study results.

## Algorithm
1. Study the data files and combine into a single data file.
2. Create a clean data file by removing the mouse with duplicates.
3. Generate summary statistics of tumor volume for each regimen.
4. Create a bar chart on the number of unique mice tested on each regimen.
5. Create a pie chart on the distribution of female and male mice.
6. Calculate final tumor volume on each mouse across four of treatment regimens.
7. Using the final tumor volume on the four drugs of interest, look for outliers and generate a boxplot.
8. Generate a line plot for a sample mouse treated with Capomulin.
9. Generate a scatter plot of average tumor volume versus mouse weight for Capomulin regimen.
10. Calculate correlation coefficient and linear regression model for the Capomulin regimen.

## Observations and Insights

1. Based on the mean and final tumor volume, the drug Ramicane shows the greatest reduction of tumor volume. Ramicane performed slightly better that the drug of interest which is Capomulin. These two drugs have the smallest standard deviation indicating that the results are more consistent than the other drug regimens. Ketapril on the other hand shows the least tumor reduction and least consistent results.

2. All drug regimen started with almost the same number of mice. The number of data points on drug regimens Ramicane and Capomulin suggests that more mice reached a later timepoint. The sex distribution in the study is almost equally split between male and female. 

3. Of the four regimens of interest, only Infubinol has an outlier which skewed the average tumor volume downwards.

4. Based on the correlation coefficient and the linear regression model, as the weight of the mouse increases, the average tumor volume increases as well.
