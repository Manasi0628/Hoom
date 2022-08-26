# Hoom
After doing a slight research on the given data, I chose some factors which affect the Home Prices in US.
* The 7 factors are as follows -
  - Delinquency Rate on Mortgages
  - Real Gross Domestic Product(GDPC1)
  - Federal Funds Effective Rate(DFF)
  - Wages
  - Unemployment Rate
  - New Houses
  - Sold Houses
* As the data was collected from an official site for key economic indicators the data had hardly any missing values.
* Data was converted on quaterly basis. Hence, up-sampling and down-sampling of data was needed as per each dataset.
* Moving further we clubbed our data in a single dataframe and checked the correlation for each factor.
* Here we can se GDP and Wages were highly corelated with the Home Prices and hence, we can say GDP and wages are the factors affecting more on the Home Prices.

* Moving on to the Modeling part. Standardizing the data was the first step needed as our data was unevenly distriburted.
* As our y variable was continuous in nature Linear Regression was most suited for this task.
* After modelling our data the Training and Test Accuracy achieved was 98% and 81% respectectively.
* After the whole evaluation of this case we can consider that GDP, Houses Sold and Wages are the most important factors Affecting the House Prices in the US.
