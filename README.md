# Andrew's Project Portfolio

Hi! My name is Andrew, and I am currently pursuing a master's degree in Applied Statistics at the University of Michigan, Ann Arbor. Below are my favorite data science projects I've completed, whether for class or out of personal interest.

## [California Wildfire Prediction](https://github.com/ngandr/Wildfires)

I read in and process over 7.5 million observations worth of data using BigQuery to visualize and classify wildfires in California from 2010 to 2020 through the Google Cloud Platform. I additionally created geospatial plots to help identify key variables that play major roles in wildfire spread, such as soil moisture, temperature, and geographic location within California. I was able to achieve a testing accuracy of 90% and f1-score of about 88% through a random forest classifier. Other models I investigated were ridge-regularized logistic regression, support vector machine, and a gradient boosted classifier.

![](/images/ca_wildfires.png)

![](/images/soil_moisture.png)

## Data Science Capstone

For my senior capstone project, I collaborated with two other data science minors to work with a client company that aims to disrupt human trafficking operations across the globe using data analytics and machine learning tools. In this case, our goal was to build a model that detects the presence of sand mines from satellite imagery, the mines are known to have cases of human trafficking of workers. We manually scraped and vectorized satellite imagery from Sentinel-2 and Google Earth in order to fit classification algorithms that predicted sand mines along numerous rivers in India. I was able to write a Python script that pulled geographic coordinates and labels from KML files that came from downloading Google Earth polygons we drew for training data. We achieved around 80% accuracy and 82$ f1-score with the data we had.

## [Cluster Analysis and Recommendations on Anime Data](https://github.com/ngandr/anime_proj)

+ Queried and cleaned data on over 3,100 observations from [AniList](https://anilist.co/), an anime database and tracking website, using GraphQL
+ Performed exploratory analysis and unsupervised learning with nominal data and user scores to find hidden clusters based on genres/tags, popularity, and overall reception
+ Gathered insights regarding which shows users generally liked or disliked, and which ones tend to be more mainstream
+ Investigated description-based and content-based text similarities to make recommendations

![](/images/eda_popularity.png)

![](/images/user_data_clusters.png)

![](/images/anime_recs_2.PNG)

## [Topic Modeling on TED Talks](https://github.com/ngandr/TED_Talks_NLP)

I cleaned and preprocessed over 4,000 English-language TED Talk transcripts and performed some exploratory data analysis on the data. I then fitted and tuned a non-negative matrix factorization model, which extracted 20 clear topics from the transcripts, achieving the highest coherence score of .319. 

![](/images/astronomer_words.png)

![](/images/topics_boxplot.png)

## [Predicting Housing Prices with Advanced Regression Techniques](https://github.com/ngandr/Housing-Regression-Analysis)

+ Performed feature engineering and selection on housing data containing over 70 different variables in R
+ Applied dimensionality reduction techniques and tuned and fitted numerous regression models including K-NN and random forest
+ Achieved highest R-squared value of .921 via extreme gradient boosted regression
        
![](/images/lot_sale_price.png)

![](/images/neighborhood_sale_price.png)

## [Basic Analysis on Anime Data](https://ngandr73.shinyapps.io/anime-app/)

I created an R Shiny app the performed basic numerical and text analyses on data scraped and cleaned from Crunchyroll

![](/images/shinyapp.png)
