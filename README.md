<h1>Linear Regression Machine Learning model</h1>
<h3>Basic Information</h3>
A Linear regression machine learning model to estimate house prices based on variables such as square footage, number of bedrooms and bathrooms, and location. It will include data processing and analysis, model training, and effectiveness testing.

There are 3 main objectives of this project:
* Identify variables that affect house prices in the set area
* Create a linear model to effectively relate house prices with the identified variables in a quantitative formatting
* Calculate the accuracy and effectiveness of the model

<h2>Data Processing</h2>

This data is from Seattle, Washington, US (sources at bottom), as UK data is more diffcult to access however the project can be applied to the UK data as long as the variables and data are valid

<h3>Null Value Check</h3>

1 line of code to check for any null values in the data - returns clean with 0.0 for each column.

<h3>Outliers</h3>

Variables put on a boxplot using the seaborn data visualisation library - showing outliers in the price plot. Using the statistic formula to remove any data that is 1.5 * IQR either side of the whiskers. This is a standard practice here in context however if the data set was average height, 6'5"+ would be removed - but is the average height of an NBA player so take into account the context of the situation

<img width="900" height="500" alt="image" src="https://github.com/user-attachments/assets/6ef3b8bc-abfd-45f2-b52b-8ac0d48feee5" />

<p align="center">
Price graph has now removed larger outliers - same will be done for each variable
 

<img width="300" height="250" alt="image" src="https://github.com/user-attachments/assets/9c566a3f-0835-4f05-9e2d-47db81ff4381" />

Done with each variable:

<img width="900" height="500" alt="image" src="https://github.com/user-attachments/assets/4b45a745-0b3a-4fc1-9c25-61455c326190" />


