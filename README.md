# Book-Recommendation-System
# Book Recommendation System

### Team Members
- Anis Fathima
- Bhargav Simha
- Sravan
- Sandhya
- Dileep

### Objective
Develop a high-quality book recommendation system to enhance conversion rates for Amazon Kindle by helping readers find books suited to their taste.

### Features
1. **Simple Recommender**: Ranks books using weighted scores based on ratings and review counts.
2. **Content-Based Filtering**: Recommends books similar to the user's preferences using cosine similarity.
3. **Collaborative Filtering**: Suggests books based on user-user or item-item similarity using KNN and SVD.

### Dataset
- Source: Goodreads API (10,000 books, 53,424 users, and 5.9M+ ratings).
- Features: Titles, authors, genres, publication years, ratings, etc.

### Methods
1. Data preprocessing:
   - Handle missing values.
   - Feature selection and engineering.
2. Exploratory Data Analysis:
   - Distribution of ratings and reviews.
3. Modeling:
   - Simple Recommender.
   - Content-Based Filtering.
   - Collaborative Filtering.

### Results
- **Simple Recommender**: Provides a ranked list of popular books.
- **Content-Based Filtering**: Personalizes recommendations using book attributes.
- **Collaborative Filtering**: Offers diverse recommendations using user interaction data.

### How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Book-Recommendation-System.git

