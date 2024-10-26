# Movie Recommendation System

A content-based movie recommendation system built using **Flask**, **Scikit-learn**, and **Natural Language Processing (NLP)**. This app recommends movies based on similarity in movie metadata and provides details about each recommended movie.  

## Table of Contents
- [About the Project](#about-the-project)
- [Tech Stack](#tech-stack)
- [Files and Directories](#files-and-directories)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Features](#features)

---

## About the Project
This project creates a content-based recommendation system that uses metadata to recommend movies similar to a given movie title. The app also includes movie details such as cast, genre, rating, and reviews.

---

## Tech Stack
- **Programming Language:** Python
- **Framework:** Flask
- **Libraries:** scikit-learn, pandas, numpy, nltk, BeautifulSoup
- **Web Server:** gunicorn

---

## Files and Directories
- **`main.py`** - Main Flask application.
- **`nlp_model.pkl`** - Serialized NLP model for sentiment analysis.
- **`tranform.pkl`** - Serialized TF-IDF vectorizer.
- **`static/`** - Contains static assets like CSS files.
- **`templates/`** - HTML templates for the web app.
- **`data1.csv`** and **`main_data.csv`** - Datasets containing movie metadata.

---

## Getting Started

### Prerequisites
- **Python 3.x** installed
- Install dependencies listed in `requirements.txt`:
    ```bash
    pip install -r requirements.txt
    ```

### Running the Application
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/movie-recommendation-system.git
    ```
2. Navigate to the project directory and run the Flask app:
    ```bash
    python main.py
    ```
3. Open your browser and navigate to `http://127.0.0.1:5000/`.

---

## Usage
1. Enter a movie title in the search bar to get a list of recommended movies.
2. Click on a recommended movie to view its details, cast, and user reviews.

---

## Features
- **Movie Recommendations**: Content-based recommendation using cosine similarity.
- **Sentiment Analysis**: NLP-based analysis of user reviews to determine review sentiment.
- **Detailed Information**: Displays cast, genres, and user ratings for each movie.
- **Auto-suggestions**: Search bar auto-suggests movie titles for easier navigation.

---

## Example Screenshots


![Screenshot (66)](https://user-images.githubusercontent.com/104056311/212107697-b6a9620b-89e6-4c41-9f33-d62b34d19675.png)
![Screenshot (67)](https://user-images.githubusercontent.com/104056311/212107756-e4e6aefa-cbda-4298-9764-6f9f9711d102.png)
![Screenshot (68)](https://user-images.githubusercontent.com/104056311/212107818-0d935ef2-ec30-4211-b5f4-e1e2636c1c9b.png)

---

## Show Some ❤️
If you enjoyed this project, consider starring the repository!

---

## License
Distributed under the MIT License. See `LICENSE` for more information.

--- 

Happy coding! 🎉


