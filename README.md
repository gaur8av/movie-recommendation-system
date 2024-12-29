# Movie Recommendation System

## Project Description
The **Content-Based Movie Recommendation System** is a machine learning application that suggests movies based on users' preferences. By analyzing movie features like genres, cast, and descriptions, the system recommends similar films to provide a personalized experience for movie enthusiasts.

## Features

- **Content-Based Filtering**: Recommends movies with similar attributes (genre, actors, etc.) to those the user has enjoyed.  
- **Personalized Recommendations**: Tailored suggestions based on individual preferences.  
- **Search**: Keyword-based search with filters for specific criteria.  

### User Profiles:
- **Explicit Data**: Ratings, reviews, watch history, genres, actors, directors, etc.  
- **Implicit Data**: Watch time, pause/rewind behavior, search history, social media interactions.  

### Movie Metadata:
- Genre, plot summary, cast, crew, release date, awards, ratings, reviews, popularity.  

## Installation Instructions
This system is based on a Streamlit web application. Follow these steps to install and run:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/movie-recommendation-system.git
   cd movie-recommendation-system
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the application:
   ```bash
   streamlit run app.py
   ```
4. Open your browser and navigate to the URL provided by Streamlit (typically `http://localhost:8501`).

## Technologies Used
- **Natural Language Toolkit (nltk)**  
- **Term Frequency-Inverse Document Frequency (TF-IDF)**  
- **Cosine Similarity**  
- **Python**  
- **Pandas**  
- **NumPy**  
- **Scikit-learn**  
- **Streamlit**

---


