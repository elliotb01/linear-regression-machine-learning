<h1>Linear Regression Machine Learning model</h1>
<h3>Basic Information</h3>
A Linear regression machine learning model to estimate house prices based on variables such as square footage, number of bedrooms and bathrooms, and location. It will include data processing and analysis, model training, and effectiveness testing.

There are 3 main objectives of this project:
* Identify variables that affect house prices in the set area
* Create a linear model to effectively relate house prices with the identified variables in a quantitative formatting
* Calculate the accuracy and effectiveness of the model

<h2>Data Processing</h2>

Data taken from: https://gist.github.com/guilhermesilveira/eb03c2f0d0fc52d4df2528b330f50914

This data is from Seattle, Washington, US as UK data is more diffcult to access however the project can be applied to the correct data

<h3>Null Value Check</h3>

1 line of code to check for any null values in the data - returns clean with 0.0 for each column.

<h3>Outliers</h3>

I plot each of the variables on a boxplot using the seaborn data visualisation library - showing outliers in the price plot. Prices above $1,500,00 are removed as they can skew the data
