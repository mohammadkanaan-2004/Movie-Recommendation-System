# 🎬 Movie Recommendation System

## 📌 Overview

This project presents a **context-based movie recommendation system** that suggests movies based on user-generated tags from the MovieLens dataset.
Unlike traditional systems that rely only on ratings, this model focuses on **contextual meaning** such as mood, themes, and user perception.

The system uses Natural Language Processing (NLP) techniques to analyze tags and generate more **personalized and relevant recommendations**.

---

## 🎯 Objectives

* Improve movie recommendation accuracy using contextual data
* Utilize user-generated tags instead of only ratings
* Apply NLP techniques for better understanding of movie features
* Build a simple and explainable recommendation model

---

## 🚀 Features

* Context-aware recommendations
* Tag-based similarity matching
* TF-IDF vectorization
* Cosine similarity algorithm
* Personalized movie suggestions

---

## 🧠 Tech Stack

* **Language:** Python
* **Environment:** Jupyter Notebook
* **Libraries:**

  * Pandas
  * NumPy
  * Scikit-learn
  * Matplotlib

---

## 📊 Dataset

This project uses the **MovieLens dataset (tags.csv)**.

Each record includes:

* `userId` → user identifier
* `movieId` → movie identifier
* `tag` → user-generated description
* `timestamp` → time of tagging

These tags represent user opinions such as:

* mood (e.g., *funny, sad*)
* genre perception (e.g., *action, romantic*)
* context (e.g., *family movie, classic*)

---

## ⚙️ How It Works

1. **Data Preprocessing**

   * Clean and prepare tag data
   * Remove noise and duplicates

2. **Feature Extraction**

   * Apply **TF-IDF vectorization** to convert text into numerical features

3. **Similarity Calculation**

   * Use **Cosine Similarity** to measure similarity between movies

4. **Recommendation**

   * Return top similar movies based on user input

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/Movie-Recommendation-System.git
cd Movie-Recommendation-System
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the notebook

```bash
jupyter notebook
```

Then open:

```
Movie_Recommendation_System_CRP.ipynb
```

---

## 📈 Results

* The system successfully recommends movies based on **semantic similarity of tags**
* Provides more **context-aware suggestions** compared to traditional methods
* Lightweight and explainable model

---

## ⚖️ Advantages

* Uses real user-generated context
* Easy to understand and implement
* No need for complex deep learning models

---

## ⚠️ Limitations

* Tags may be inconsistent or noisy
* No explicit mood or time data
* Limited to available dataset

---

## 🔮 Future Work

* Add **hybrid recommendation system** (content + collaborative filtering)
* Integrate **deep learning models**
* Improve tag preprocessing with NLP techniques
* Add user interface (web app)

---

## 👨‍💻 Author

**Mohammad Kanaan**
Computer Science Student

---

## 📜 License

This project is licensed under the MIT License.
