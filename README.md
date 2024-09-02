# Lyrics-Generator-Model-Using-Recurrent-Neural-Networks



## About the Project

This project leverages Long Short-Term Memory (LSTM) neural networks to generate song lyrics that mimic the style and structure of existing music. By training on a dataset of lyrics, the model learns to produce coherent and contextually relevant text based on a given seed. Through techniques like tokenization and one-hot encoding, combined with the Adam optimizer, the model generates high-quality lyrical content. This work highlights the creative potential of AI in the music industry, showcasing the power of machine learning in artistic expression.


## Project Structure

- **Lyric-Gen_RNN.ipynb**: The primary Jupyter Notebook containing all the steps from data exploration and preprocessing to model training and lyric generation.
- **README.md**: Detailed description of the project (this file).
- **output**: The graph illustrates the "Training Loss over Epochs" for a lyrics 
generator model utilizing an RNN with LSTM units. The x-axis 
represents the epochs (0 to 4), and the y-axis indicates the training loss, 
decreasing from approximately 1.84 to 1.75.

## Features

- **Exploratory Data Analysis (EDA):**
  - Summary statistics of the dataset including the distribution of characters, words, and sentences.
  - Visualizations like histograms and word clouds to understand the data.
  
- **Data Preprocessing:**
  - Text cleaning: Removing special characters, converting text to lowercase.
  - Corpus creation: Building a vocabulary from the song lyrics.
  - Feature and target generation for training the model.
  
- **Model Training:**
  - LSTM-based neural network trained on character sequences.
  - Hyperparameter tuning and performance monitoring using loss visualization.
  
- **Lyrics Generation:**
  - Generates new song lyrics based on a seed phrase provided by the user.
  - The model predicts one character at a time, allowing for flexible and creative outputs.

## Dataset
The dataset used for training the lyric generation model is sourced from Kaggle and is named AZLyrics. For the sake of simplicity and efficiency, a single CSV file, **azlyrics_lyrics_w.csv**, has been utilized. This file contains a comprehensive collection of song lyrics, which was instrumental in training the model to generate coherent and creative lyrics. Using this dataset allowed for a streamlined development process while still providing a rich variety of text data for effective model training.

 ## Prerequisites

- **Python 3.x**
- **Jupyter Notebook**
- **Libraries:**
  - TensorFlow
  - Keras
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - NLTK
  - WordCloud
  - Pillow


 ## Cloning the Repository
To clone the repository and navigate to its directory, use these commands:

```bash


```
