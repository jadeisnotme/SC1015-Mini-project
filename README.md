# SC1015 DSAI Project: Movie Success

**Our Motivation:**
The movie industry has become a bustling and dynamic space, with millions of viewers eagerly awaiting new releases. The excitement is palpable, especially on platforms like YouTube, where movie trailers often garner thousands of comments and reviews, indicating audience anticipation and reaction. This vibrant environment creates a rich dataset of sentiments that can be analyzed to understand audience perception and predict a movie's potential success.

![pexels-tima-miroshnichenko-7991579](https://github.com/stabmerightnow/SC1015-Mini-Project/assets/102968942/e0b7f4e4-5d41-4416-8acb-24df526f3774)

## Project Goal:
In this project, our goal is to use data analysis and machine learning techniques to predict a movie's success, providing valuable insights for investors, producers, and marketers. By leveraging data from YouTube movie trailer comments, we aim to understand the factors that contribute to a movie's success and predict its gross revenue. This predictive analysis can be crucial for stakeholders to make informed investment decisions.

## Dataset Used:
The dataset used for this project is `movies_youtube_sentiments.csv`, obtained from [Kaggle](https://www.kaggle.com/datasets/dineshvasired/movies-youtube-trailers-and-sentimentdinesh-dinesh/code). It contains a variety of information related to movies, including sentiment scores from YouTube comments, budget, gross revenue, release year, and more.

## Jupyter Notebooks:
- [Data Preparation]
- [Data Visualisation]
- [Predict Movie's Gross Revenue]
- [Predict Movie's Success]
- [Overall Datainsights]


<br>

---

# Overview of DataScience Pipeline:
### [Data Preparation]<br>
- To ensure the analysis is relevant and accurate, we focused on data from the year 2000 onwards.
- Remove unnecessary data. 

### [Data Visualisation]<br>
- Histograms to understand the distribution of variables.
- Density curves to visualize data trends.
- Correlation matrices to identify relationships between variables.
- Scatter plots to explore possible correlations.
- Boxplots to examine the distribution and outliers of numerical data.
- 
### [Predict Movie's Gross Revenue]<br>
- Linear Regression
- Random Forest
- Decision Tree
- Gradient Boosting Machines
- Artificial Neural Network

### [Predict Movie's Success] <br>
- Logistic Regression
- Random Forest
- Decision Tree
- Gradient Boosting Machines
- Artificial Neural Network
- Convolutional Neural Network

### Key Insights & Recommendations:
- Youtube sentiments have **little** impact on movies' gross revenue
- Budget and votes have relatively **significant** impact on gross revenue, but they are not deterministic
- Only **few** stars, writers and directors have a large impact on gross revenue
- Random Forest and Gradient Boosting Machines are relatively more accurate in predicting gross revenue
- The Artificial Neural Network and Logistic Regression demonstrate a better performance to predict movie success 


<br>

# What we learnt from this project:
- Encoding categorical variables as numerical
- Linear Regression, Polynominal Regression, Logistic Regression
- Tree models (random forest, decision tree, gradient boosting can be used for both regression and classficiation)
- Artificial Neural Network and Convolutional Neural Network
- Mean Squared Error, Mean Absolute Error, R-squared
- Accuracy, Precision, Usefulness, Recall, F1-Score

<br>

# Contributions:
**Data Preparation:** `Charlene` `Hathaway` `Jiayu` <br>
**Data Visualisation:** `Hathaway` `Jiayu` `Charlene` <br>
**Machine Learning:** `Jiayu` `Hathaway` `Charlene` <br>


# References:
- https://www.kaggle.com/datasets/dineshvasired/movies-youtube-trailers-and-sentimentdinesh-dinesh/code
- https://patshih.luddy.indiana.edu/publications/Gao-MovieSuccess-iConf19.pdf
- https://pythonhacker.blog.csdn.net/article/details/124892318
- https://www.researchgate.net/publication/354790470_Movie_Success_Prediction_Using_Data_Mining
