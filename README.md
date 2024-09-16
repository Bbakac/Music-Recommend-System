# Music Recommendation System

This project implements a Music Recommendation System using Spotify's API and machine learning techniques. It fetches data from Spotify and clusters songs based on their features to provide music recommendations.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Requirements](#requirements)
- [Contributing](#contributing)
- [License](#license)

## Overview
The **Music Recommendation System** allows users to find songs similar to a given list of songs by using features such as acousticness, danceability, energy, and more. The system utilizes the Spotify API to retrieve song metadata and audio features, and it applies KMeans clustering for song recommendations.

## Features
- Fetches song data from Spotify using Spotipy (Spotify's API wrapper).
- Applies KMeans clustering to group similar songs.
- Recommends songs based on provided input tracks.
- Provides detailed insights into song features (e.g., energy, tempo, etc.).

## Installation

To run the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Music_Recommendation_System.git



Usage

Open the Music Recommendation System notebook.
Input your Spotify API credentials if not already set.
Provide a list of songs to get recommendations based on their audio features.
The system will output recommended songs that are similar to the input tracks.
Requirements

Python 3.x
Spotipy
Pandas
Scikit-learn
Seaborn
Matplotlib
Jupyter Notebook

