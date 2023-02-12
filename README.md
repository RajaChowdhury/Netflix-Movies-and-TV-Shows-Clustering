# Netflix Movies and TV-Shows Clustering
                                              AlmaBetter Verified Project
![image](https://user-images.githubusercontent.com/104791753/218310481-368b73c1-ad29-4e8f-8efa-bbb968d098ea.png)

I have built a content based clustering model using Python which can be deployed to provide a better user experience and to increase customer engagement and satisfaction.

## Description

This project is about Netflix Movies and TV Shows where third-party Netflix search engine released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. This excited me to explore what all other insights can be obtained from the same dataset.

The problem statement of Netflix movies and TV show clustering is to group similar content based on a set of features such as genre, cast, director, ratings, etc. This is done in order to make recommendations to the users based on their viewing history and preferences. The goal is to create homogeneous groups of content that are similar in terms of these features, so that users can easily find new content that they are likely to enjoy.



## **Attribute Information**

1. **show_id** : Unique ID for every Movie / Tv Show

2. **type** : Identifier - A Movie or TV Show

3. **title** : Title of the Movie / Tv Show

4. **director** : Director of the Movie

5. **cast** : Actors involved in the movie / show

6. **country** : Country where the movie / show was produced

7. **date_added** : Date it was added on Netflix

8. **release_year** : Actual Releaseyear of the movie / show

9. **rating** : TV Rating of the movie / show

10. **duration** : Total Duration - in minutes or number of seasons

11. **listed_in** : Genere

12. **description**: The Summary description


## Steps Involved


* Importing Libraries And Loading The Datasets
* Overview Of The Dataset
    *   Reading & Inspection Of Dataset
    *   Further analysing the datasets
* Data Wrangling And Pre-Processing
    *   Null Value Treatment
    *   Handling Outliers
    *   Converting Dtype Of Feature
    *   Combining And Creating Columns
    *   Extracting Month From Date
* Exploratory Data Analysis
* Key Findings From EDA
* Data Preparation For NLP
    *   Download NLTK
    *   Removing Punctuations
    *   Removing Stopwords
    *   Stemming
    *   Tfidf Vectorizer 
* Feature Engineering 
    *   Feature Selection
    *   StandardScaler
* ML Model
    *   Silhouette score
    *   Elbow Method
  	*   DBSCAN
  	*   Dendrogram
  	*   Agglomerative Clustering
*  Conclusions 

## Dataset

The dataset can be downloaded from: https://drive.google.com/file/d/1APF_osBeVvwaPngDl968MgD0SaL_Q6O7/view?usp=share_link
