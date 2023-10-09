# Netflix-Movies-and-TV-Shows-Clustering
# Objective
The goal of the Netflix Movies and TV Show clustering project is to enhance the organization of content and improve the recommendation system on the Netflix platform. This project aims to achieve several key business objectives:

Enhancing Content Discovery: The project seeks to improve the way users discover content by grouping similar movies and TV shows together.

Personalized Recommendations: It aims to enhance the recommendation system by suggesting content from the same clusters to users, making recommendations more tailored to individual preferences.

Facilitating Content Curation: The project will enable the creation of thematic content collections, simplifying user navigation and increasing engagement by offering curated content.

Informed Content Licensing: By gaining insights from content clusters, Netflix can make more informed decisions regarding licensing and acquiring new content.

Boosting User Engagement: The ultimate goal is to increase user engagement and retention by providing content that aligns with individual preferences and interests.

# Approach:-

step 1: As the first step, viewing and cleaning the data, I mounted the drive, imported the required libraries, and then stored the data in variables to produce actionable insights. We next analyzed our data distribution using univariate, bivariate, and multivariate plots as the next step in the data analysis and visualization process. There was a multicollinearity check.

Step 2: Replaced some entries with null, some with the phrase "unknown," and some were omitted because the presence of null values could have caused issues in the following steps.

Step 3: As part of the feature engineering process, processed textual data, including contraction expansion, lower case conversion, punctuation and stopword removal, normalization, and vectorization. We used standardscalar for data scaling.

stage 4: As the final stage, clustering was carried out using various methods. I used K-Means, ElbowCurve, DBSCAN, Dendogram, and Agglomerative Clustering.

# Conclusion

I tried 5 models for ML i.e.

K-means clustering,
 Elbow curve, 
 DBSCAN,
 Hierarchical clustering,
 Agglomerative clustering,
K-means clustering shows that '4' will be the optimum no of clusters with the silhouette score.  Elbow curve cross-validation was giving optimum number of clusters as 11.

