# Netflix-Movies-and-TV-Shows-Clustering

This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset was gathered through the third-party Netflix search engine Flixable. The amount of TV series available on Netflix has almost tripled since 2010, according to an interesting analysis that was published in 2018. Since 2010, the number of films available on the streaming service has dropped by more than 2,000, although the number of TV episodes has nearly tripled. Investigating what further insights may be drawn from the same dataset will be intriguing.

Approach:-

step 1: As the first step, viewing and cleaning the data, I mounted the drive, imported the required libraries, and then stored the data in variables to produce actionable insights. We next analyzed our data distribution using univariate, bivariate, and multivariate plots as the next step in the data analysis and visualization process. There was a multicollinearity check.

Step 2: Replaced some entries with null, some with the phrase "unknown," and some were omitted because the presence of null values could have caused issues in the following steps.

Step 3: As part of the feature engineering process, processed textual data, including contraction expansion, lower case conversion, punctuation and stopword removal, normalization, and vectorization. We used standardscalar for data scaling.

stage 4: As the final stage, clustering was carried out using various methods. I used K-Means, ElbowCurve, DBSCAN, Dendogram, and Agglomerative Clustering.

I tried 5 models for ML i.e.

K-means clustering,
 Elbow curve, 
 DBSCAN,
 Hierarchical clustering,
 Agglomerative clustering,
K-means clustering shows that '4' will be the optimum no of clusters with the silhouette score. But Elbow curve cross-validation was giving optimum number of clusters as 11.

Thus K-means clustering will be best for this data set.
