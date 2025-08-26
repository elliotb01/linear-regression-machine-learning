<h1>Linear Regression Machine Learning model</h1>
<h3>Basic Information</h3>
A Linear regression machine learning model to estimate house prices based on variables such as square footage, number of bedrooms and bathrooms, and location. It will include data processing and analysis, model training, and effectiveness testing.

<h4>There are 3 main objectives of this project:</h4>
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

Done with each variable to get data that fits into a usable data set for predictions

<img width="900" height="500" alt="image" src="https://github.com/user-attachments/assets/4b45a745-0b3a-4fc1-9c25-61455c326190" />

<h2>Training Model</h2>

The data is normalised and assigned to y and x training values to be applied to a Linear Regression

RFE is used to eliminate features from the dataset for selection

<h2>Statistics Model</h2>

Error terms graph with a scatter graph to represent the training - then evaluation of the model
<p align="center">
<img width="300" height="250" alt="image" src="https://github.com/user-attachments/assets/4943aa07-0c19-4278-91f7-c51c2ba4e3b5" /><img width="300" height="250" alt="image" src="https://github.com/user-attachments/assets/8940553a-6db9-48f7-9867-167bf153fa9a" />

<h2>Prediction</h2>

Prediction results with 0.5445 or 54.45% effectiveness
<p align="center">
<img width="300" height="250" alt="image" src="https://github.com/user-attachments/assets/05200edd-9173-48e1-82a9-d8084447a00f" />

<h2>Final Thoughts</h2>

This project is the first 'Machine Learning' project I have undertaken, I found it challenging yet rewarding, using and undestanding new frameworks such as RFE was difficult but my knowledge has definitely improved through this project.

Although I wanted a higher effectiveness it is about expected with this data set as it is the entire of Seattle which has a lot of variation so having a prediction higher than 60-70% would be unexpected.

Sources I used for this project:

Housing data:

https://gist.github.com/guilhermesilveira/eb03c2f0d0fc52d4df2528b330f50914

Articles:

https://www.geeksforgeeks.org/data-science/detect-and-remove-the-outliers-using-python/
https://www.kaggle.com/code/ashydv/housing-price-prediction-linear-regression/notebook#Data-Cleaning
