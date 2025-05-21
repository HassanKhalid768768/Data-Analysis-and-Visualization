# 🎌 Anime Recommendation System

An intelligent and hybrid anime recommendation system that combines **Collaborative Filtering** and **Content-Based Filtering** to suggest relevant anime titles based on user preferences, genres, and ratings. The system leverages **web scraping**, **MAL API**, and **neural network-based modeling** to deliver personalized recommendations.

---

## ✅ Features

- 🔍 Scrape anime metadata from **MyAnimeList** using Selenium  
- 📡 Fetch rich data using the **MAL API**  
- 🧠 Collaborative Filtering via neural network embeddings  
- 📚 Content-Based Filtering using TF-IDF and cosine similarity  
- 📊 Genre-based WordClouds and EDA visualizations  
- 🧪 Evaluation through loss plots, Q-Q plots, and residual analysis  
- ⚙️ Option to deploy via Flask/Streamlit web app  

---

## 🤖 Recommender Systems

### 🧠 Collaborative Filtering

- Embedding layers for users & anime  
- Dot product + dense layers  
- Early stopping, learning rate scheduler  
- Provides both user-based and item-based suggestions  

### 🧬 Content-Based Filtering

- TF-IDF vectorization on genres and synopsis  
- Cosine similarity matrix  
- Recommends similar titles based on anime content features  

---

## 📈 Evaluation

- ✅ Training vs validation loss plot  
- ✅ Actual vs predicted ratings visualization  
- ✅ Residual & Q-Q plots for distribution checks  
- ✅ K-Fold cross-validation using linear models  
- 🔧 Optional metrics: RMSE, Precision@K for top-N recommendation evaluation  

---

## 🔧 Enhancements & Ideas

- 🔁 Hybrid model combining collaborative and content-based filtering  
- 🧵 Asynchronous MAL API fetching with multithreading  
- 🗃 Efficient data storage using SQLite or Parquet  
- 🌐 Real-time recommender using Flask or Streamlit  
- 👤 User authentication and profile-based recommendation  

---

## 📦 Requirements

- Python 3.8+  
- Libraries:
  - TensorFlow
  - Pandas
  - NumPy
  - Scikit-learn
  - Selenium
  - Requests
  - BeautifulSoup
  - Matplotlib
  - Seaborn
  - Plotly
  - WordCloud
  - Flask or Streamlit *(optional for deployment)*

---

🎉 **Start building intelligent anime recommendations today!** 🍱

---

## 🎥 Project Demo

> 📺 **Watch the demo video here**:  
> [Anime Recommender Demo](https://github.com/user-attachments/assets/fd6c943b-fc0f-486d-a844-854337da5997


)

