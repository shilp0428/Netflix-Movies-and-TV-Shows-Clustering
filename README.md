# Netflix-Movies-and-TV-Shows-Clustering
Netflix Movies and TV Shows Clustering
-----------------------------------------------------
💾 Table of Content
- Introduction 
- Abstract 
- Dataset Information
- Problem Statement
- Conclusion

📖 Introduction:

- Netflix is a well-known entertainment provider that is used by millions of people all over the world.

This EDA will use Python libraries, matplotlib, and Seaborn to examine the Netflix dataset through visualizations and graphs.

As of 2019, the dataset contains TV shows and movies available on Netflix. Fixable, a third-party Netflix search engine, provided the data for this study.

Machine learning has a wide range of applications in our organization. Personalization has long been the most well-known application of machine learning, which fuels our recommendation systems.

We're also utilizing machine learning to assist in designing our movie and TV programme portfolio by identifying traits that lead to successful content.

We utilize it to help Netflix's rapidly expanding studio streamline the creation of original movies and TV shows.

We can also employ machine learning to improve video and audio encoding, adaptive bitrate selection, and our in-house Content Delivery Network, which handles more than a third of all internet traffic in North America.

Our major goal in this project is to identify clusters based on similar content by matching text-based features such as the description column, which in our case is a brief summary description of the contents.

-----------------------------------------------------

📖 Abstract:
- The objective was to anticipate bunches of comparable substance by matching text-based elements.

Exploratory Data Analysis is done on the dataset to get the insights from the information however the principal invalid qualities are taken care of. Likewise, some hypothesis testing was additionally performed from the experiences from EDA.

After that description segment is our objective variable must be highlighted where NLP activities are performed on it and after that vectorized by utilizing TFIDF.

From that point forward, all that was left was to track down the clusters and fit our models by knowing various clusters, and further, the model is assessed utilizing the metrics.

-----------------------------------------------------

📖 Dataset information:
- Show id: Unique ID for every Movie / Tv Show

- type – Identifier - A Movie or TV Show

– Title of the Movie / Tv Show

- director-director of the content

- cast Actors involved in the movie / show

- country – Country where the movie / show was produced

- date added – Date it was added on Netflix

- release year – Actual Release year of the movie / show

- rating – TV Rating of the movie / show

- duration – Total Duration - in minutes or number of seasons

- listed in – genre

- description – The Summary description

-----------------------------------------------------

📖 Problem Statement:

- This dataset consists of TV shows and movies available on Netflix as of 2019.

The dataset is collected from Flexible which is a third-party Netflix search engine

In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010.

The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled.

It will be interesting to explore what all other insights can be obtained from the same dataset.

Integrating this dataset with other external datasets such as IMDB ratings, rotten tomatoes can also provide many interesting findings.

-----------------------------------------------------

📖 Conclusion:

- Our main goal in this project was to determine different clusters based on content, which we have done.

After using the Silhouette score and the elbow method, we found that 28 clusters would be suitable.

which we evaluated using the Davies-Bouldin index and the Calinski-Harabasz score.

Our clusters were homogeneous within clusters and heterogeneous with respect to other clusters.


