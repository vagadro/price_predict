**ML Project-COMMODITY PRICE PREDICTION**

**Web app:** https://pricepredict-vagadro.herokuapp.com/

**Overview:** In this project, I have tried to identify predicted price of a laptop depending on the configurations choosen by the user like screen size, resolution, company, weight, ssd/hdd size, ram size etc. This project depicts a classical way of predicting outputs having real numbers and is generally called Regression problem.

**Dataset used:** The dataset consists of data of approx 1300 latops with different configurations. The data was scraped from internet and was locally saved. 

**Approach:** A very simple approach was followed to build the model and the results were deployed using Streamlit app running on heroku server.
- Data Loading
- EDA: identification of outliers, correlation between features etc
- Data Cleaning,preprocessing and feature engineering: Since the dataset has many columns which can be directly fed into the model due to high number of unique values, features were bined together wherever necessary ( like CPU type, Operating system type), feature engineering to create complex features like screen resolution, SSD/HDD size etc were performed
- Model Building: Since data contained categorical features, the same were converted into numerical using OneHotEncoder. Multiple regression models were build like Linear Regression, Ridge Reg, Lasso Reg, Decision Tree, SVM, Random Forest, ADA/Gradient/XG Boost and Voting Regressor in this step
- Model Evaluation: Best model was evaluated on R2Score and Mean Absolute Error too
- Final Model: Random Forest model was finalised due to best scoring
- Deployment: Model deployed using Streamlit framewok using heroku server


Best,

Deepak Rawat

Linkedin: linkedin.com/in/deepak-rawat-183316b5
