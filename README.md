# Spotify-Clustrs
This project aims to cluster Spotify songs based on their audio features using unsupervised machine learning techniques. The dataset contains various attributes of songs, including energy, danceability, key, mode, time signature, and more. By grouping similar songs together.
Project Description

This project aims to cluster Spotify songs based on their audio features using unsupervised machine learning techniques. The dataset contains various attributes of songs, including energy, danceability, key, mode, time signature, and more. By grouping similar songs together, we can discover patterns and insights about musical characteristics across different clusters.

The main steps of the project include:

Data Loading and Cleaning:
Importing the Spotify dataset (SpotifyFeatures.csv) and inspecting the data for missing values.
Dropping non-numerical and irrelevant columns like artist_name, track_name, track_id, and genre.
Feature Engineering and Preprocessing:
Encoding categorical features (key, mode, time_signature) using one-hot encoding.
Scaling all numerical features with StandardScaler to ensure uniformity for clustering.
Clustering with KMeans:
Using the Elbow Method to determine the optimal number of clusters.
Fitting the KMeans model on the scaled dataset and assigning cluster labels to each song.
Visualization and Analysis:
Plotting key audio features like energy vs danceability colored by cluster to interpret the results.
Identifying characteristics of each cluster and understanding song grouping patterns.
Tools and Libraries Used
Python for all data processing and modeling.
Pandas & NumPy for data manipulation.
Matplotlib & Seaborn for visualization.
Scikit-learn for preprocessing, clustering, and evaluation.
Potential Applications
Music recommendation systems based on song similarity.
Understanding musical trends and song characteristics.
Assisting DJs, playlists curators, and music analysts in categorizing songs efficiently.
