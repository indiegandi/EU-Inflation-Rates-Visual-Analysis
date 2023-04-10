Comparing European Countries' Inflation Rates over the Years (2000-2022)
This Jupyter Notebook provides a comparison of the inflation rates of European Union countries between the years 2000 and 2022. The data is visualized using Python packages such as pandas, geopandas, and Plotly.

The data used in this analysis is stored in the 'inflation.csv' file, which is read using pandas. The missing data is checked using the 'missingno' package, and the irrelevant columns are dropped.

To conduct the analysis, the dataset is divided by inflation types such as headline, energy, food, core, and producer, and only the core inflation rate is used for the analysis. The DataFrame is transposed using pandas to make it more readable and easier to analyze. A sub-dataframe is created for the European Union countries. A list of EU countries is defined to filter out the data, and only EU countries with data from 2000 onwards are included in the sub-dataframe.

Finally, the data is visualized using Plotly. First, a line chart is created to show the trend of inflation rates in EU countries over time. Then, an animated choropleth map is created to show the inflation rates of different EU countries in different years.

In addition, the missing data is handled by replacing the NaN values with mean values. NaN values are counted by country, and a list of EU countries, including and excluding the eurozone countries, is defined. The NaN values of the eurozone countries are replaced with the mean value of the respective country.

Overall, this notebook provides a comprehensive analysis of inflation rates in EU countries, which can help understand the trend of the inflation rate of each country, which can be used for further research or analysis.
