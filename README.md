# Line Bot Project
This project is a Music Recommendation Line Bot that provides various functionalities such as music recommendations,weather information, jokes, and more. 
* Introduction video : https://youtu.be/TWYkBG3NkN4
* Project demo : https://youtu.be/o7za_xxgrCw 

## Features
1. Weather Information: Users can inquire about the weather in a specific location.
2. Music Recommendations: The bot suggests songs based on the user's mood or the current weather conditions.
3. Jokes: Users can request jokes for a good laugh.
4. YouTube Search: The bot can search for YouTube videos based on user input.

## File Intro
1. app.py : (main file) connect to line and combine different services
2. bert.py: BERT model
3. crawel_lyrics.py: crawel the lyrics from azlyrics
4. similarity.py: using cosine similarity to calculate the similarity of two embedding
5. fine_tunedBert.ipynb: train the model and save the result 


## Installation
* To run this project locally, follow these steps:
1. Clone the repository.
2. Install dependencies using pip install -r requirements.txt.
3. Change the Line Bot API by providing your channel access token and channel secret (app.py).
4. Run the Flask application using python app.py.

## Usage
1. Add the Line Bot to your Line account.
2. Interact with the bot by sending messages related to weather, music, jokes, etc.
3. Follow the bot's responses.


## Requirements
```
Flask==2.0.2
scikit-learn==0.24.2
line-bot-sdk==1.19.0
configparser==5.0.2
numpy==1.21.2
pyimgur==0.7.7
requests==2.26.0
scipy==1.7.1
pandas==1.3.3
youtube-search-python==1.4.3
datasets==1.14.0
torch==1.9.0
tqdm==4.62.3
matplotlib==3.4.3
tez==0.1.4
transformers==4.10.3
```
