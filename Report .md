




![WhatsApp Image 2021-12-18 at 3 47 31 PM](https://user-images.githubusercontent.com/58592557/146673235-a693d62a-9b19-4baf-8549-1f05409625a3.jpeg)












<h1> Abstract: </h1>
Prediction of the correct IMDB gross is essential for the movie industry and decreasing market risk. The
success and failure of the movie depend on movie-related variables. Therefore, the goal of this project is to
create a machine learning model that will predict the US movies gross taking into consideration many features.
The features include IMDb rating, certification of movie, number of votes, release year, movie duration, and
metascore. Exploring data scraped from the IMDb websites to see which features affect the prediction the most.

<h1> Design: </h1>
The progress of this project will be as follows. First gathering data using web scraping but the data was so small 1k abservation and then we decided to choose another dataset from Kaggle 5k abservation , then exploratory Data
Analysis (EDA) will be performed on the data we gathered. Finally, preparing data to be used in different
regression models. In this project, we analyze the relationship between the target variable “Gross” and the
features “duration, num_voted_users, cast_total_facebook_likes, facenumber_in_poster, budget, title_year, aspect_ratio”.

<h1> Data: </h1>
The dataset used in this project was extracted from IMDb website. we traied dataset from Kaggle to match our needs
in order. There were 5000 movies with 28 features initially.
The dataset becomes almost 3000 records with 20 features after we have done some cleaning and feature engineering
on the original dataset.

<h1> Algorithms: </h1>
<h2> ● Feature Engineering: </h2>
1. Convert categorical features to dummy variables.
2. Subtracting interactive terms in order to make the feature more relevant. that solved the multicolinaerty in the columns.
<h2> ● Models:</h2>
We have explored many regression machine learning models
in order to choose the best for our case. The models are linear regression, K-fold linear regression,
Polynomial regression, Ridge regression,lasso regression and random forest. The data was splitted into 60 percent
training, 20 percent validating, and 20 percent testing. The model we selected was polynomial regression
with degree 2 and 3 because it shows the best score between all models.

<h3> Best Model: Polynomial regression with degree 2 and 3: </h3>
   - Polynomial Training Score: 0.54368493
   - Polynomial Testing score: 0.53247904
<h1> Tools: </h1>
<h3> ● Technologies: </h3> Jupyter Notebook, google colab, spyder, Python.
<h3> ● Libraries: </h3> Pandas, NumPy, Matplotlib, Seaborn, Request, BeautifulSoup, plotly, patsy, holoviews, hvplot, and Sklearn.

<h1> Communication: </h1>



<img width="308" alt="Screen Shot 2021-12-18 at 10 31 02 PM" src="https://user-images.githubusercontent.com/58592557/146673141-c0159db0-dffd-4432-8bf0-34b5600265a6.png">



<img width="404" alt="Screen Shot 2021-12-19 at 2 20 36 PM" src="https://user-images.githubusercontent.com/58592557/146673123-76426776-e23c-43e3-9af9-bac234d73a33.png">


![WhatsApp Image 2021-12-18 at 10 58 03 PM](https://user-images.githubusercontent.com/58592557/146673219-759b1736-bbbf-44c5-818f-d76e6c959d86.jpeg)
