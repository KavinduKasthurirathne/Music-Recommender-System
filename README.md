# Music Recommender System 🎵

This is a web application built using Streamlit and Spotipy to recommend music based on a selected song. The app leverages a similarity matrix to provide personalized recommendations.

## Features
- Recommend five songs based on the similarity to the selected song.
- Display album covers for each recommended track.
- Interactive dropdown to select a song for recommendations.

## Data Collection
Dataset Link: https://drive.google.com/file/d/129PzdVgBFa5S6aeswndJuROYDMjYjT-i/view?usp=sharing

## Methodology
### 1. Data Collection:
Collected data from Spotify and other sources, which includes song names, artists, and descriptions.

### 2. Text Preprocessing:
- Cleaned and preprocessed the data by removing special characters, punctuation, and converting text to lowercase.
- Tokenized song descriptions into individual words or phrases.
- Removed stop-words to focus on meaningful content.

### 3. Feature Extraction:
- Used **TF-IDF (Term Frequency-Inverse Document Frequency)** to convert textual data into numerical representations.

### 4. Building a Recommender Model:
- Implemented **Content-Based Filtering** to recommend songs similar to the one selected by the user.
- Calculated similarity scores between songs using their feature representations.

### 5. User Interaction and Recommendations:
- Allows users to select a song from the dropdown menu.
- Displays the top 5 recommended songs along with their album covers.

## Outputs
### Example 1


### Example 2


## How to Run
1. Clone this repository.
2. Run the Model.ipynb first.
3. Run the app using the command:
   ```bash
   streamlit run app.py
