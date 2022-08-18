# Netflix_Recomender_systems


The data is related to Netflix movies and tv shows till 2019. It is understandable from the 
data that tv shows number has been tripled from 2010 and the number of movie titles has been 
reduced by 2000. We have to find several insights from the data using EDA and also, have to 
cluster the data based on the data.

------------------------------------------------------------------------------------------------------

Coming to the main part processing the text data using NLTK library and performing those 
actions on description feature. After that we have removed all the stop words and applied 
stemming to it (Stemming is the process of reducing a word to its word stem that affixes to 
suffixes and prefixes or to the roots of words known as a lemma). After that finding lengths of 
features and storing new features for clustering.
Standardized all the data before performing Ml Model in this case we used Kmeans algorithm 
because after seeing the analysis done we thought this is the algorithm can balance all the 
features. Plotted Silhouette for the optimal Kvalues and Elbow plot for cluster size and we found 
out the optimal clusters can be used are 21.
Performed Recommender systems using cosine similarity because The cosine similarity is 
beneficial because even if the two similar data objects are far apart by the Euclidean distance 
because of the size, they could still have a smaller angle between them. Smaller the angle, higher 
the similarity.
The recommendations after all the tuning and model selection we are getting pretty good range 
of recommendations and satisfied with the recommendations.
The given Netflix dataset has been successfully analysed and visualised by various plots and 
charts and the final result recommendations are very ppsitive
