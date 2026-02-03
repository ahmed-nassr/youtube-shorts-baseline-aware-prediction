# YouTube Shorts: EDA & Baseline-Aware Prediction
#### Project status: completed.
## About this project:
This is a Data Science-oriented project that focuses on exploratory data analysis (EDA) of YouTube Shorts performance data and an experimental machine learning pipeline to evaluate whether view counts can be predicted from available features.
## Goals:
The main objectives of this project are to perform EDA on the data, provide meaningful insights, and evaluate whether ML models are able to predict the view count of a YT Short based on the other present metrics while keeping in mind the baseline RMSE.
## Methodology:
The project was done using Python on Jupyter notebook.\
Markdown cells were used to explain almost every part, clarifying the reasoning and conclusions behind each step to improve interpretation.

Throughout the process, the following techniques were used to give reasonable insights and conclusions:
- Exploratory Data Analysis
- Outlier inspection
- Data Visualization
- Feature engineering
- Train/validation/test splitting
- Data preprocessing & scaling
- Pipeline engineering
- Baseline modeling
- GridSearchCV
- Model evaluation with RMSE
## Conclusion:
Since the baseline RMSE is lower than the predicted RMSE of the best ML model from GridSearch, I concluded that the data in the dataset may not be sufficient enough to build an accurate ML model that is able to predict the view count of YT Shorts. The data may have been too small, too noisy, or simply inaccurate for ML models to be able to detect patterns and correlations between the data, resulting in the need for more accurate data.

This proves that baseline-aware model evaluation is critical for knowing whether the target feature is predictable or not.
## Python Packages used:
- NumPy
- Pandas
- Matplotlib
- Seaborn
- scikit-learn
- category-encoders
- XGBoost
## About the data:
The dataset contains performance insights of 300 YouTube Shorts, covering shorts across multiple categories such as Tech, Travel, Food, Comedy, Lifestyle, and Education.\
It includes the following detailed metrics:
- Duration (in seconds)
- Hashtag count
- Views
- Likes
- Comment count
- Shares
- Upload hour
- Category
### Source:
The dataset was sourced from kaggle and can be found in:
https://www.kaggle.com/datasets/prince7489/youtube-shorts-performance-dataset
