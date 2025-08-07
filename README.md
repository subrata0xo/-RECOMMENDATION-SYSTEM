# -RECOMMENDATION-SYSTEM

*COMPANY* : CODTECH IT SOLUTIONS

*NAME* : SUBRATA SAMANTA

*INTERN ID* : CT08DG249

*DOMAIN* : MACHINE LEARNING

*MENTOR* : NEELA SANTOSH 

The project titled "Bollywood Movie Recommendation System" aims to build a basic recommendation engine using a dataset of Bollywood movies and their associated popularity metrics such as YouTube views, likes, dislikes, budget, and box office collections. The primary goal is to simulate a recommendation system that suggests similar movies based on content and engagement features, due to the absence of explicit user feedback or ratings in the dataset.

The dataset used, bollywood.csv, consists of 149 entries of Bollywood movies, including fields such as movie name, release date, genre, release time, budget, box office collection, YouTube views, likes, and dislikes. Since no user ID or user interaction data is available, traditional collaborative filtering could not be applied. Instead, a content-based filtering approach was adopted to develop the recommendation system.

The process begins with data exploration and preprocessing. Using Python libraries such as pandas, the dataset was loaded and cleaned. Key numerical features (BoxOfficeCollection, YoutubeViews, YoutubeLikes, and YoutubeDislikes) were selected for defining the movie profile. These features were then normalized using StandardScaler to ensure all variables contributed equally to the similarity calculation.

Once scaled, a cosine similarity matrix was computed using the sklearn.metrics.pairwise module. This matrix calculates the degree of similarity between movies based on the selected features. Higher similarity values between two movies indicate that they are more similar in terms of their performance and audience engagement on YouTube and at the box office.

A recommendation function was created to return the top N most similar movies when a user inputs a specific movie title. This function leverages the cosine similarity matrix to sort and retrieve the highest-scoring related movies, excluding the input movie itself.

To make the notebook more informative and engaging, data visualization techniques were also included. Visualizations such as the distribution of box office collections, genre distribution, top 10 most viewed movies, and a correlation heatmap of the features were created using matplotlib and seaborn. These plots helped in understanding the underlying patterns and relationships between various features, adding value to the exploratory data analysis phase.

Despite being a simplified recommendation system, this project showcases how content-based approaches can be used effectively when explicit user data is not available. It highlights the importance of feature engineering, similarity metrics, and visualization in building intelligent systems that mimic real-world recommendation engines used by streaming platforms.

In conclusion, this project provided hands-on experience in handling real-world datasets, applying machine learning concepts like similarity analysis, and presenting insights through visualizations. It is a foundational step toward building more complex systems involving collaborative filtering, hybrid models, or deep learning-based recommender systems. With further data enrichment (e.g., user reviews or ratings), the system can be extended to offer personalized recommendations and improve overall accuracy and relevance.

#OUTPUT :

