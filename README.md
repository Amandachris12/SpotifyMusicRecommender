
# Spotify Data Analysis and Music Recommendation System

## Overview

This project presents a complete data science workflow using Spotify music datasets. It includes data loading, exploratory data analysis, clustering, and the development of a content-based music recommendation system. The project was implemented in Python using Google Colab and demonstrates the application of machine learning techniques to analyze music data and generate song recommendations.

---

## Objectives

The objectives of this project are to:

- Load and preprocess Spotify datasets.
- Explore and analyze patterns within the data.
- Visualize trends in music features across different years and genres.
- Apply clustering algorithms to identify groups of similar songs and genres.
- Build a content-based music recommendation system using audio features.
- Integrate the Spotify Web API to retrieve song information when required.

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Scikit-learn
- Spotipy
- Spotify Web API
- WordCloud

---

## Repository Structure

```
Spotify-Data-Analysis/
│
├── Phase1_Data_Loading.ipynb
├── Phase2_EDA.ipynb
├── Phase3_Clustering.ipynb
├── Phase4_Recommendation_System.ipynb
├── README.md
└── requirements.txt
```

---

## Project Phases

### Phase 1: Data Loading and Preprocessing

- Imported the Spotify datasets into Python.
- Loaded the datasets using Pandas.
- Examined the dataset structure and summary statistics.
- Performed initial data exploration.
- Created additional features to support later analysis.

### Phase 2: Exploratory Data Analysis

- Analyzed distributions of songs across decades.
- Explored relationships between audio features.
- Visualized music trends using various charts.
- Generated a genre word cloud.
- Identified patterns in the Spotify dataset through statistical analysis.

### Phase 3: Clustering Analysis

- Standardized numerical audio features.
- Applied K-Means clustering to songs and genres.
- Visualized genre clusters using t-SNE.
- Visualized song clusters using Principal Component Analysis (PCA).
- Interpreted clustering results to identify groups of similar music.

### Phase 4: Music Recommendation System

- Connected to the Spotify Web API using Spotipy.
- Retrieved song information through the Spotify API.
- Implemented helper functions for song retrieval and feature extraction.
- Computed mean feature vectors for selected songs.
- Used cosine similarity to recommend songs with similar audio characteristics.
- Tested the recommendation system using multiple song inputs.

---

## Machine Learning Techniques

This project applies several machine learning and data analysis techniques, including:

- Data preprocessing
- Feature scaling
- Exploratory data analysis
- K-Means clustering
- Principal Component Analysis (PCA)
- t-Distributed Stochastic Neighbor Embedding (t-SNE)
- Cosine similarity
- Content-based recommendation

---

## Dataset

The project uses Spotify datasets containing audio and metadata attributes such as:

- Song title
- Artist
- Release year
- Danceability
- Energy
- Acousticness
- Instrumentalness
- Loudness
- Tempo
- Popularity
- Valence
- Speechiness
- Duration

These features are used for analysis, clustering, and generating music recommendations.

---

## Requirements

The project depends on the following Python libraries:

- pandas
- numpy
- matplotlib
- seaborn
- plotly
- scikit-learn
- spotipy
- wordcloud

Install the required packages using:

```bash
pip install -r requirements.txt
```

---

## Future Improvements

Possible enhancements to this project include:

- Deploying the recommendation system as a web application using Streamlit.
- Improving recommendation accuracy through hybrid recommendation techniques.
- Integrating collaborative filtering methods.
- Displaying album artwork and song previews.
- Expanding the recommendation engine with additional Spotify metadata.

---

