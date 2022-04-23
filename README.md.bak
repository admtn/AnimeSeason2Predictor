# Welcome to Anime Season 2 Predictor repository
![Welcome Image](https://www.meme-arsenal.com/memes/c8914885099656b0430179c51ffe6f91.jpg)
## About
Welcome to our Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on anime data from the Kaggle dataset [Anime Recommendation Database 2020](https://www.kaggle.com/datasets/hernan4444/anime-recommendation-database-2020). 

For detailed walkthrough, please view the source code in order from:
1. [Data Extraction](https://github.com/nicklimmm/movie-analysis/blob/main/data-extraction.ipynb)
2. [Data Visualization](https://github.com/nicklimmm/movie-analysis/blob/main/data-visualization.ipynb)
3. [Data Resampling and Splitting](https://github.com/nicklimmm/movie-analysis/blob/main/data-resampling-and-splitting.ipynb)
4. [Decision Tree Classifier](https://github.com/nicklimmm/movie-analysis/blob/main/logistic-regression.ipynb)
5. [Random Forest Classifier](https://github.com/nicklimmm/movie-analysis/blob/main/logistic-regression.ipynb)
6. [Gradient Boosting Classifier](https://github.com/nicklimmm/movie-analysis/blob/main/neural-network.ipynb)

---
## Problem Definition
##### What is the probability of an anime getting a Season 2?
##### An anime getting a season 2 has an impact on multiple demographics. It not only impacts the consumer, but also the content creators and the merchandise producers. 

##### Being able to accurately predict if an anime will get a second season will help people be able to better prepare themselves when the season 2 drops:
- Consumers - Prepare Snacks, Schedule Watching time, Organize watch parties, Deal with anxiety of not knowing if there will be a season 2
- Online Content Creators - Prepare content by reading news/rumors/source materials
- Merchandise Producers - Able to take an informed decision on producing merchandise for the anime
---
## Choosing our Dataset
After browsing many datasets on Kaggle, our team decided that the Anime Recommendation Dataset is the most useful one to us. It is recently up-to-date, with many upvotes. It includes 17558 up-to-date Anime data with potentially useful columns such as Genres, Scores, Ranked, Popularity, Members etc. The data included in this dataset is based on the popular Anime Community website, [MyAnimeList]([MyAnimeList.net](https://myanimelist.net/)).

## Data Cleanup
However, the dataset is not perfect. It has too many columns and also no way to tell if an anime has a sequel as there is no relationship between any data entry. Thus we need to comb through each value and find sequels and include a relationship variable between them. (HasSequel and SequelName). This can be found in Data Cleanup File.

---
## EDA
We explored the numerical and categorical columns in our dataset, namely:
- Score
- Type
- Source
- Ranked

We found out that Sequels have better scores, Sequels tend to be Ranked higher, and that there is a higher percentage of Sequels that come from Manga then any other medium.

## Models Used
1. Decision Tree Classifier
2. Random Forest Classifier
3. Gradient Boosting Classifier

## Conclusion
We are able to accurately predict if an anime does have a sequel with the variables Score, Ranked and Source. Our accuracy rate is consistently above 70% when provided with this values but only when using the Gradient Boosting Classifer with sampled data.

Sampling the data was a very important step in our project as without it, we were having poor accuracy results, consistently between the 30~50% range. 

## What did we learn from this project?
- Resampling, How to handle imbalanced datasets
- Random Forest, An improved version of decision trees, making use of a collection of trees
- Gradient Boosting Classifier, Better performer decision tree algorithm compared to Random Forest

## Contributors

- Adam Tan Jun Xiang 
- Lim Shi Bin 
- Arun Ezekiel

## References

