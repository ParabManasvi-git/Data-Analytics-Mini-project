# Data-Analytics-Mini-project
# 🎬 Movie Recommendation System

A **Content-Based Movie Recommendation System** developed using **Python** and **Machine Learning**. This project recommends movies similar to a user's selected movie by analyzing features such as genres, keywords, cast, and director using **CountVectorizer** and **Cosine Similarity**.

---

## 📌 Project Overview

This recommendation system helps users discover movies similar to their favorite ones. Instead of relying on user ratings, the system uses **content-based filtering**, where movies are compared based on their metadata.

The project performs data preprocessing, feature extraction, vectorization, and similarity calculation to generate accurate recommendations.

---

## ✨ Features

- 🎥 Recommend similar movies
- 🔍 Search movies by title
- 📊 Content-Based Recommendation
- ⚡ Fast similarity search
- 🧠 Machine Learning based
- 💻 Simple and beginner-friendly implementation

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- CountVectorizer
- Cosine Similarity
- Jupyter Notebook

---

## 📂 Dataset

The dataset contains the following information for each movie:

- Movie Title
- Genres
- Keywords
- Cast
- Director

These features are combined to generate recommendations.

---

## ⚙️ How It Works

1. Load the movie dataset.
2. Handle missing values.
3. Select important features:
   - Genres
   - Keywords
   - Cast
   - Director
4. Combine selected features into a single text column.
5. Convert text into numerical vectors using **CountVectorizer**.
6. Calculate similarity scores using **Cosine Similarity**.
7. Accept a movie title from the user.
8. Display the top recommended movies.

---

## 🧠 Machine Learning Technique

### Content-Based Filtering

The recommendation system suggests movies that have similar content to the selected movie.

### Algorithms Used

- CountVectorizer
- Cosine Similarity



## 📦 Requirements

```
pandas
numpy
scikit-learn
jupyter
```

Install manually:

```bash
pip install pandas numpy scikit-learn jupyter
```

---

## 💻 Example Output

```
Enter Movie Name:

Avatar

Recommended Movies

1. Guardians of the Galaxy
2. John Carter
3. Star Trek
4. Interstellar
5. Jupiter Ascending
```
<img width="308" height="248" alt="Image" src="https://github.com/user-attachments/assets/e5fedd46-b07b-4fa5-9f9f-442ee924ccad" />
<img width="581" height="248" alt="Image" src="https://github.com/user-attachments/assets/e5141a4b-2f72-446e-82fe-b43dcffcab0a" />

---

## 📈 Future Improvements

- 🌐 Streamlit Web Application
- 🎬 Movie Posters using TMDb API
- ⭐ User Rating System
- ❤️ Favorite Movies List
- 🔐 User Authentication
- 🤖 Hybrid Recommendation System
- 📱 Responsive Web Interface

---

## 🎯 Learning Outcomes

- Data Preprocessing
- Feature Engineering
- Text Vectorization
- CountVectorizer
- Cosine Similarity
- Recommendation Systems
- Machine Learning Fundamentals
- Python for Data Analysis

---

## 👨‍💻 Author

**Manasvi Parab**

Computer Engineering Student  
Aspiring Data Scientist | Machine Learning Enthusiast

---

## 📄 License

This project is developed for educational purposes and is free to use for learning and academic projects.

---

