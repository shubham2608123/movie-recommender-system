# 🎬 Movie Recommender System

A **Machine Learning based Movie Recommender System** that suggests similar movies based on user selection.
The system uses **content-based filtering** and displays recommended movies with their posters using the TMDB API.

---

## 🚀 Features

* Select any movie from the dropdown
* Get **Top 5 recommended movies**
* Displays **movie posters**
* Built with **Streamlit interactive UI**
* Uses **TMDB API** for fetching posters
* Fast recommendations using **precomputed similarity matrix**

---

## 🧠 Machine Learning Technique

This project uses **Content-Based Filtering**.

Steps used:

1. Movie dataset preprocessing
2. Feature engineering using tags
3. Text vectorization using **CountVectorizer**
4. Similarity calculation using **Cosine Similarity**
5. Recommend movies based on similarity score

---

## 🛠 Technologies Used

* Python
* Pandas
* Scikit-learn
* Streamlit
* Pickle
* TMDB API
* Jupyter Notebook

---

## 📂 Project Structure

```
movie-recommender-system
│
├── app.py                # Streamlit web application
├── movie_recommender.ipynb  # Jupyter notebook for model building
├── movies_dict.pkl       # Movie dataset (processed)
├── similarity.pkl        # Similarity matrix
├── tmdb_5000_movies.csv  # Dataset
├── tmdb_5000_credits.csv # Dataset
└── README.md
```

---

## ▶ How to Run the Project

### 1 Install Dependencies

```
pip install pandas streamlit scikit-learn requests
```

### 2 Run the Streamlit App

```
streamlit run app.py
```

The app will open in your browser.

---

## 🎥 Demo

Select a movie and the system will recommend **5 similar movies with posters**.

---

## 📊 Dataset

Dataset used:
TMDB 5000 Movie Dataset

Includes:

* Movie title
* Cast
* Crew
* Genres
* Keywords

---

## 🌐 API Used

Movie posters are fetched using the **TMDB API**.

---

## 📌 Future Improvements

* Add **search functionality**
* Add **movie ratings**
* Improve **UI like Netflix**
* Deploy the app online

---

## 👨‍💻 Author

Shubham Dalvi

---

⭐ If you like this project, consider giving it a **star on GitHub**!
