# Hollywood-Ratings-and-Profit

# Statistical Learning

> Marie Hasegawa 

## Appendix of File
-Hasegawa_7045_Hollywood
  - .RHistory
  -Hasegawa_dmtm-project
   - data
      - HollyWoodMovies.txt
   - report
      - HollyWood_Ratings_Profit
      - HollyWood_Ratings_Profit_print.html
   - README.html
   - READ.md
   - .RHistory


## Appendix of Report
- Appendix
- Library of Packages
- Project Overviw
- Explaratory Data Analysis
  - `Profitability` Column
  - `AudienceScore` Column
- Methods
  - `Profitability` vs. `AudienceScore` Grouped by `HighProfit` 
  - `Profitability` and `AudienceScore` K-Means Clustering
    - Elbow Method and Silhouette method to determinine optimal clusters
    - K-Means Clustering of k=2,3,4
  - `Profitability` Column
    - Decision Tree `Profitability`
      - With Categorical Variables
      - Removed Categorical Variables
    - Bagging
    - Random Forest
    - Random Forest with Boosting
    - Model Comparison High `Profitability`
  - `AudienceScore` Column
    - Decision Tree `Profitability`
      - With Categorical Variables
      - Removed Categorical Variables
    - Bagging
    - Random Forest
    - Random Forest with Boosting
    - Model Comparison High AudienceScore
- Conclusion
  

## Final Project

The purpose of this project is to see if text mining techniques can ease better analysis for categorizing movies with just the `Descriptions` while ignoring the `Genre`from the dataset, `IMDB_movies.csv`, which is stored under the dataframe variable, `movies_desc`. 

- Tokenization (TF-DF) was used to increase efficiency to analyze term frequencies in movie `Descriptions`, so that the conceptual theme of a movie franchise would be determined even if a person has never watched any of the films. 
- Create mixtures of terms that are correlated to every topic and the mixture of topics that distinguishes each document through Topic Modeling in the dataset, `IMDB_movies.csv`.
- Sentimental Analysis focused on Movies with Sentimetal Clusters that were using `bing` and `nrc` lexicons to see how `Sentiment` affects `Rating` and `Revenue`. 
- The network of bigrams for the Movies dataset help summarize how frequented Movie `Description` word-terms create term reklationships and how they connect to other movies.

## References
Fonseca, L. (2019, August 15). Clustering analysis in R using K-means. Retrieved April 24, 2021, from https://towardsdatascience.com/clustering-analysis-in-r-using-k-means-73eca4fb7967

Hidayatuloh, A. (n.d.). Visualize Clustering Using ggplot2. Retrieved April 24, 2021, from https://rpubs.com/aephidayatuloh/clustervisual

Michel Kana, P. (2020, February 24). Data clustering tutorial for advanced. Retrieved April 24, 2021, from https://towardsdatascience.com/clustering-for-data-nerds-ebbfb7ed4090

K-means cluster analysis. (n.d.). Retrieved April 24, 2021, from https://afit-r.github.io/kmeans_clustering

Rashmi, Kassambara 06 May 2020 The demo data used in this tutorial is available in the default installation of R. Juste type data(“USArrests”) Reply, & Kassambara. (2018, October 21). K-Means clustering in R: Algorithm and practical examples. Retrieved April 24, 2021, from https://www.datanovia.com/en/lessons/k-means-clustering-in-r-algorith-and-practical-examples/
