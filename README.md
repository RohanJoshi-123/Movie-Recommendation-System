# Movie-Recommendation-System
# Movie Recommendation System Using Collaborative Filtering

## Project Overview

This project builds a Movie Recommendation System using collaborative filtering.
The system recommends movies to users based on the ratings given by similar users.

Recommendation systems are widely used in platforms like Netflix, Amazon, and YouTube to improve user experience by suggesting relevant content.

---

## Objective

The objective of this project is to:

* Understand how recommendation systems work
* Implement collaborative filtering
* Calculate similarity between users
* Recommend movies based on user preferences

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook

---

## Dataset

The dataset used contains movie ratings given by users.

Dataset Columns:

* user_id – Unique identifier for each user
* movie_id – Unique identifier for each movie
* rating – Rating given by the user
* timestamp – Time when the rating was given

---

## Project Workflow

1. Import required Python libraries
2. Load the dataset
3. Perform basic data exploration
4. Create a user–movie matrix
5. Compute user similarity using cosine similarity
6. Build a recommendation function
7. Recommend movies to users based on similar user preferences

---

## Key Concept: Collaborative Filtering

Collaborative filtering recommends items by analyzing user behavior.

If two users have similar movie preferences, the system recommends movies liked by one user to the other.

---

## Output

The system generates personalized movie recommendations for a user based on ratings from similar users.

Example:

User 1 → Recommended Movies → Movie 12, Movie 7, Movie 25, Movie 3, Movie 19

---

## Future Improvements

* Add movie titles instead of movie IDs
* Implement item-based collaborative filtering
* Use matrix factorization techniques like SVD
* Build a simple recommendation interface

---

## Conclusion

This project demonstrates how machine learning techniques can be used to build a basic recommendation system. Collaborative filtering helps provide personalized recommendations and improves user engagement.
