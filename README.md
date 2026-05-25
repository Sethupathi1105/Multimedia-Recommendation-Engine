# 🎬 Multimedia Recommendation Engine

A personalized movie recommendation system combining 
Collaborative Filtering and Content-Based Filtering techniques, 
served through a Netflix-style Flask web portal.

---

## 🎯 Problem Statement

Generic movie platforms suggest popular titles — not 
personalized ones. This engine analyzes user behavior, 
genre affinity, and textual metadata to deliver 
recommendations that actually match individual preferences.

---

## ⚙️ How It Works

User selects a movie or enters preferences
        ↓
TF-IDF vectorizes movie descriptions, genres & tags
        ↓
Cosine Similarity computes item-level relevance scores
        ↓
KNN & Matrix Factorization find similar user patterns
        ↓
Top-N personalized recommendations returned
        ↓
Results displayed in Netflix-style UI with feedback loop

---

## 🚀 Features

- Hybrid approach — Content-Based + Collaborative Filtering
- TF-IDF vectorization on descriptions, genres, and tags
- Cosine Similarity for item-level relevance scoring
- KNN and Matrix Factorization for user pattern matching
- 4,000+ movies dataset with rich metadata
- Real-time movie search with dynamic results
- Feedback loop that reduces irrelevant suggestions by 25–30%
- Netflix-style UI built with Flask

---

## 📊 Performance

| Metric                         | Result   |
|--------------------------------|----------|
| Recommendation Relevance Score | 85%+     |
| Accuracy over Baseline         | +30–35%  |
| Cosine Similarity Precision    | 88–92%   |
| Irrelevant Suggestion Reduction| 25–30%   |

---

## 🛠️ Tech Stack

| Layer          | Technology               |
|----------------|--------------------------|
| Language       | Python 3.9+              |
| ML Library     | Scikit-learn             |
| Data Processing| Pandas, NumPy            |
| Vectorization  | TF-IDF (Scikit-learn)    |
| Algorithms     | KNN, Matrix Factorization|
| Similarity     | Cosine Similarity        |
| Web Framework  | Flask                    |
| Frontend       | HTML, CSS, JavaScript    |

---

## 📁 Project Structure

movie-recommendation/
├── app.py                  # Flask entry point
├── recommender.py          # Core recommendation logic
├── content_based.py        # TF-IDF + Cosine Similarity
├── collaborative.py        # KNN + Matrix Factorization
├── data/
│   └── movies.csv          # Dataset (4000+ movies)
├── templates/
│   └── index.html          # Netflix-style UI
├── static/
│   └── style.css
├── requirements.txt
└── README.md

---

## 🔧 Setup & Run

# Clone the repo
git clone https://github.com/Sethupathi1105/movie-recommendation.git
cd movie-recommendation

# Install dependencies
pip install -r requirements.txt

# Run the app
python app.py

# Open in browser
http://localhost:5000

---

## 💡 Use Cases

- Movie streaming platforms
- E-commerce product recommendations  
- News article suggestions
- Music playlist generation

---

## 🔮 Future Improvements

- Add deep learning embeddings (Word2Vec, BERT)
- Integrate real user ratings via API
- Deploy on Render or Hugging Face Spaces
- Add A/B testing for recommendation strategies
