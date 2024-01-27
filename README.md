# Netflix-Movies-and-TV-Shows-Clustering

# **Netflix Dataset Analysis and Recommendation System**

The Netflix Dataset, which is a collection of films and TV series up to 2019, will be examined in this study. It was sourced from the independent search engine Flixable. The main goal is to employ natural language processing (NLP) to classify the information into relevant clusters so that a recommendation system can improve user experience. With over 220 million subscribers as of right now, this approach will assist Netflix in reducing subscriber churn.

Additionally, by examining the dataset, this research aims to find important patterns and insights in the streaming entertainment sector.

**Project Overview** The project was carried out in the following step-by-step process:

**Handling Null Values:** To guarantee the accuracy and integrity of the data, null values in the dataset were addressed.

**Managing Nested Columns:** To facilitate improved visualization and analysis, nested data-containing columns, including director, cast, listed_in, and nation, were handled.

**Binning Ratings:** To make analysis and recommendations easier, the rating attribute was divided into groups such as adult, kid-friendly, family-friendly, and not rated.

**Creating Clusters:** The information was grouped according to attributes such as director, cast, nation, genre, rating, and description using clustering algorithms. The TF-IDF vectorizer was used to tokenize, preprocess, and vectorize these properties.

**Dimensionality Reduction:** In order to enhance performance and get rid of noise, Principal Component Analysis (PCA) was used to reduce the dimensionality of the dataset.

**Clustering Algorithms:** To generate clusters, the Agglomerative Hierarchical Clustering and K-Means Clustering techniques were both used. Using a variety of evaluation techniques, the ideal number of clusters was found to be four for K-Means and two for hierarchical clustering.

**Content-Based Recommender System:** To offer customers tailored recommendations, a content-based recommender system was created utilizing the cosine similarity matrix. The objective was to lower subscription attrition by providing interesting and relevant material.

It is anticipated that the thorough research and suggestion system created for this project would raise customer satisfaction levels, which will eventually increase Netflix's subscriber retention rates.


# **Conclusion**
The initiative intends to improve customer satisfaction and lower Netflix member churn by using this in-depth study of the Netflix dataset and creating a content-based recommendation system. Better grouping and organizing are made possible by the content clustering, and user choices inform the recommender system's individualized suggestions. It is anticipated that these initiatives would increase user retention rates, which will help Netflix stay ahead of the competition as a top streaming entertainment provider.
