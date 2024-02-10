# Waze Churn Project Overview 
This project first does a ETL of the dataset. In that process it handles any outliers, replaces null values, merges columns before analyzing. In the analysis phase various data columns were observed in BoxPlots and Histograms with Seaborn to identify any reasons for the churn. There were a number of observations from the analysis that were then asked with the Waze team before Statistical Analysis could be applied. Some of the products and packages used are Jupyter Lab, Pandas, Matplotlib, Seaborn, Tableau



# Attached are a few of the Boxplots and histograms
1. For sessions - The number of occurrences of a user opening the app during the month. he sessions variable is a right-skewed distribution with half of the observations having 56 or fewer sessions. However, as indicated by the boxplot, some users have more than 700.
   
![](https://github.com/mpaturi/python_tableau/blob/main/images/sessions-boxplot.png?raw=true)
![](https://github.com/mpaturi/python_tableau/blob/main/images/sessions-histogram.png?raw=true)
![](https://github.com/mpaturi/python_tableau/blob/main/images/TableauBoxPlot-Sessions.png?raw=true)
