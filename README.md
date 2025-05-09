# Content-Based News Recommendation System

This project implements a **Content-Based Recommendation System** that suggests news articles based on a user's interests using **TF-IDF** and **cosine similarity**. The system analyzes article content (titles and abstracts) and compares it to a user profile built from their selected keywords or categories.

---

## Dataset

We use the [MIND (Microsoft News Dataset)](https://www.kaggle.com/datasets/arashnic/mind-news-dataset/data), which includes rich metadata for thousands of news articles, such as:

- `title`: Headline of the article
- `abstract`: Short summary
- `category` / `subCategory`: Topic classification

---

## Features

- Load and preprocess large-scale news data
- Extract text features using **TF-IDF**
- Build user profile vectors from custom keywords
- Compute **cosine similarity** between user interests and articles
- Return top-N relevant recommendations

---

## Project Structure


---

## How to Run

1. **Install dependencies**
   ```bash
   pip install -r requirements.txt

