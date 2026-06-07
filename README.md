# movie-recommended-system
A content-based Movie Recommendation System built with Python, Streamlit, and Machine Learning. It recommends similar movies based on genres, keywords, cast, crew, and movie metadata using vectorization techniques, helping users discover movies they are likely to enjoy.
---

# 🎬 Movie Recommendation System

A content-based Movie Recommendation System that suggests movies similar to the one selected by the user. The project uses machine learning and natural language processing techniques to analyze movie metadata such as genres, keywords, cast, crew, and overview to generate accurate recommendations.

## 🚀 Features

* Recommend movies similar to a selected movie
* Content-based filtering approach
* Interactive Streamlit web application
* Fast recommendation generation
* Clean and user-friendly interface
* Uses movie metadata for similarity calculation

## 🛠️ Tech Stack

* Python
* Streamlit
* Pandas
* NumPy
* Scikit-Learn
* NLTK
* Pickle

## 📂 Project Structure

```text
movie-recommendation-system/
│
├── app.py
├── movies.pkl
├── similarity.pkl
├── requirements.txt
├── README.md
└── datasets/
```

## ⚙️ How It Works

1. Movie data is collected and preprocessed.
2. Important features such as genres, cast, crew, keywords, and overview are combined.
3. Text data is vectorized using CountVectorizer.
4. Cosine similarity is calculated between movies.
5. When a user selects a movie, the system finds and displays the most similar movies.

## 🔧 Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/movie-recommendation-system.git
cd movie-recommendation-system
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Environment

**Windows**

```bash
venv\Scripts\activate
```

**Mac/Linux**

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

## ▶️ Run the Application

```bash
streamlit run app.py
```

The application will open in your browser automatically.

## 📊 Machine Learning Approach

* Data Preprocessing
* Feature Engineering
* Text Vectorization using CountVectorizer
* Cosine Similarity Calculation
* Recommendation Generation

## 🎯 Future Improvements

* Hybrid Recommendation System
* User Authentication
* Personalized Recommendations
* Movie Posters and Details Integration
* Collaborative Filtering
* Deployment on Cloud Platforms

## 🤝 Contributing

Contributions, issues, and feature requests are welcome.

## 📜 License

This project is licensed under the MIT License.

## 👨‍💻 Author

Developed with Python and Machine Learning for movie recommendation and discovery.

