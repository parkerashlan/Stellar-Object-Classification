# Stellar Object Classification
I use logistic regression and SVM to classify galaxies, stars, and quasars from the Sloan Digital Sky Survey DR16 database. In the "classifying-galaxies-stars-quasars" notebook, I use a dataset from Kaggle which pulls the top 100,000 entries in the database with the u and g values within a certain range. In the "Classifying with Logistic Regression and SVM" notebook, I use an original query into the database which grabs equal amounts of stars, quasars, and galaxies to train and 100,000 entries randomly to test on.

# Packages Required
* statsmodels==0.11.1
* seaborn==0.10.1
* scikit-learn==0.23.1
* pandas==1.0.5
* numpy==1.18.5
* matplotlib==3.2.2

# Description of Notebooks
Each notebook is organized in the same way. Each of them are split into steps of the process as such:

0. Goal
1. Exploratory Data Analysis/Cleaning the Data
2. Feature Engineering
3. Training the Model
4. Conclusion

# Acknowledgments
Kaggle Dataset: https://www.kaggle.com/muhakabartay/sloan-digital-sky-survey-dr16
SDSS DR16 Database: http://skyserver.sdss.org/dr16/en/tools/search/sql.aspx

