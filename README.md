# Unsupervice-ML-Capstone-Project-Rushikesh-Mane-NETFLIX-MOVIES-AND-TV-SHOWS-CLUSTERING
This is a capstone project on NETFLIX MOVIES AND TV SHOWS CLUSTERING which is a unsupervised ML project . 
Netflix is a subscription-based streaming service that allows our members to watch TV shows and movies on an internet-connected device.Depending on your plan, you can also download TV shows and movies to your iOS, Android, or Windows 10 device and watch without an internet connection. If you're already a member and would like to learn more about using Netflix, visit Getting started with Netflix. Netflix is a streaming service that offers its users a wide variety of TV shows, movies, and documentaries. It is available on most devices, including computers, phones, and tablets. Netflix has a monthly subscription fee, but it also offers a monthly subscription plan that allows users to watch unlimited movies and TV shows. Netflix also offers a monthly subscription plan that allows users to watch unlimited movies and TV shows with no commercials. Netflix also offers a monthly subscription plan that allows users to watch unlimited movies and TV shows with no commercials and no late fees.

## Project Summary:
This dataset consist data form 2010 to 2018. Our objective is to conduct an Exploratory Data Analysis to understand what content is available in different countries and if Netflix has been increasingly focusing on TV rather than movies in recent years. And use these insights to cluster similar content by matching text-based features.

After loading the data, we start by observing the first and last five values to understand the dataset. Next, we treat the null values by dropping them if the respective variables contain <1% of null values. This is followed by feature engineering to extract new variables from the datetime variable date_added.

This cleaned data is then used to conduct EDA in order to understand it better and identify the underlying trends.

Once obtained the required insights from the EDA, we start with Pre-processing the text data by removing the punctuation, and, stop words. This filtered data is passed through TF - IDF Vectorizer since we are conducting a text-based clustering and the model needs the data to be vectorized in order to predict the desired results.

Finally, K–Means clustering is utilized to form 10 distinct clusters with similar data points
## Problem Statement 
In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset. We will be able to understand the shows that are similar to and different from one another by creating clusters, which may be leveraged to offer the consumers personalized show suggestions depending on their preferences.

## Contains Of Project:

1.Exploratory Data Analysis (EDA)

2.Understanding the Data

3.Cleaning the Data

4.Feature Engineering

5.Clusters Impanelment

6.Building recommendation system

7.Conclusions

8.Future Scope

# **Conclusion:**

*It was interesting to find that majority of the content available on Netflix is Movies.

*But in the recent years it has been focusing more on Tv-Shows.

*Most of these contents are released either in the year ending or the beginning.

*United States and India are among the top 5 countries that produce all of the available content on the platform.

*Also 6 of the actors among the top ten actors with maximum content are from India.

*TV-MA tops the charts, indicating that mature content is more popular on Netflix.

*k=10 was found to be an optimal value for clusters using which we grouped our data into 10 distinct clusters.

*Using the given data a simple recommender system was created using cosine_similarity and recommendations for Movies and Tv Shows were obtained.
