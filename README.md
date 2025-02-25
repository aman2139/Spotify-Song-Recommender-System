# Spotify-Song-Recommender-System

This project aims to leverage the music recommendation system's ability to analyze song features and similarities to inform the design of new personalized discovery features, enhancing user engagement and creating tailored music exploration journeys. I have aimed to design an innovative feature for Spotify to improve user engagement through personalized music discovery experiences. 

My Recommendation Model, on the other hand, delivers precisely matching songs based on the user's input. Our objective is to boost user engagement by creating personalized music discovery features through data-driven analysis of song attributes and similarities. Moreover, users can enhance their recommendations by adjusting various song attributes such as loudness, speechness, danceability, and more. The system generates personalized recommendations based on unique parameters for each song, including danceability, mood, genre, valence, tempo, and loudness, among others.

The database used is till 2020 and has no songs to recommend released after 2020. The accuracy and relevance of recommendations are highly dependent on the completeness, diversity, and accuracy of the dataset used. If the dataset lacks variety or contains outdated information, the recommendations may not reflect current user preferences.

I have provided a Tableau workbook named `Spotify Song Recommendation Dashboard.twb` that users can download and interact with to gain a deeper understanding of the utilized database. Additionally, I have included a PowerPoint presentation that clearly outlines the objectives behind building the model, the construction process, and how it operates.

The code implements a Spotify song recommendation system using a dataset of songs and their features. It leverages a graphical user interface (GUI) built with tkinter to allow users to input a song name and adjust sliders for various feature weights (e.g., tempo, loudness, popularity). The system uses cosine similarity to compute the closest matches based on the user's input and selected weights, and then displays a list of recommended songs. If the entered song name doesn't match exactly, the program suggests the closest match from the dataset, ensuring usability.

The purpose was to put the starter code in the `started_spotify_eda` file, and the code for the UI shown to the user which the user interacts with as well, in the `spotify_recommender` file which is run through the terminal in VS Code. THE REST ARE JUST SUPPLEMENTARY FILES REQUIRED TO RUN THE CODE.

The dataset has been derived from Kaggle(https://www.kaggle.com/code/tubaniksarl/music-recommendation-system).
