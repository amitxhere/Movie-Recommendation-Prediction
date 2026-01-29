# 🎬 Movie Recommendation System

## 📌 Overview
This project is a **content-based movie recommendation system** built using **Python** and **Machine Learning**. It recommends movies similar to a user’s favorite movie by analyzing movie metadata such as genres, keywords, cast, director, and tagline. The system uses **TF-IDF vectorization** and **cosine similarity** to measure similarity between movies.

---

## 🚀 Features
- Content-based movie recommendations  
- TF-IDF vectorization for text processing  
- Cosine similarity to find similar movies  
- Fuzzy matching to handle incorrect or partial movie names  
- Simple and beginner-friendly implementation  

---

## 🛠️ Technologies Used
- Python  
- NumPy  
- Pandas  
- Scikit-learn  
- Difflib  

---

## 📂 Dataset
The dataset contains movie-related information including:
- Title  
- Genres  
- Keywords  
- Tagline  
- Cast  
- Director  

Missing values are handled to ensure smooth text processing and accurate similarity calculations.

---

## 🧠 How It Works
1. Selected movie features are combined into a single text feature  
2. Text data is converted into numerical vectors using **TF-IDF Vectorizer**  
3. **Cosine similarity** is calculated between all movie vectors  
4. User input is matched with the closest movie title using **difflib**  
5. Movies with the highest similarity scores are recommended  

---

## ▶️ How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/movie-recommendation-system.git
## 2.Install required libraries:
pip install numpy pandas scikit-learn

## 3.Run the Jupyter Notebook:
jupyter notebook Movie_Reccomendation.ipynb

