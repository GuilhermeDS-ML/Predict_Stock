# Working with Time Series in Stock Forecasting

### Objective:

Although this project involves predicting the price of a stock (BBAS3), its true purpose is to demonstrate the practice of dealing with Time Series. The intention is to highlight the process required to handle this type of data, rather than focusing on the results applied to the stock market. 

It was an educational exercise and served as a practice to enhance my skills in time series data analysis.

### About the Data: 

The data was obtained via the MetaTrader5 API and from the website [investing.com](https://br.investing.com/). 

The observations are daily, and apart from the date, all variables represent the closing prices of the asset. I will use four assets: BBAS3 (Target), BBSE3, Gold, and Dollar Value.

### Road Map
<ul>
<li>Import and load data</li>
<li>Prepare data<ul>
<li>Overview</li>
<li>Decompose</li>
<li>Autocorrelation</li>
<li>Stationarity<ul>
<li>Variable "close"<ul>
<li>Attempt 1 - Simple transformations</li>
<li>Attempt 2 - Differentiation</li>
</ul>
</li>
<li>BBSE3</li>
<li>USD-BRL</li>
<li>GOLD_USD</li>
<li>Day &amp; Month</li>
</ul>
</li>
</ul>
</li>
<li>Preprocessing<ul>
<li>Normalizing exogenous variables</li>
<li>Normalizing target variable</li>
</ul>
</li>
<li>Modeling<ul>
<li>ARIMA<ul>
<li>Train</li>
<li>Validation</li>
</ul>
</li>
<li>Prophet<ul>
<li>Preparing the Datasets</li>
<li>Train</li>
<li>Validation</li>
</ul>
</li>
</ul>
</li>
</ul>

### References
- [investing.com](https://br.investing.com/)
- [Data Science Academy](https://www.datascienceacademy.com.br/)
