# spotify-genre-segmentation
Minor project using clustering &amp; recommendation on Spotify data

# 🎧 Spotify Songs' Genre Segmentation – Minor Project

This project explores and segments songs from the Spotify dataset using **machine learning and clustering techniques**.  
It simulates how Spotify might group similar tracks to improve recommendations.

---

## 🧠 Objective

> "To analyze musical features and group songs into meaningful clusters using KMeans, enabling personalized song recommendations."

---

## 📁 Dataset

We used a Spotify dataset containing:
- Playlist genre
- Playlist name
- Audio features: danceability, energy, valence, tempo, acousticness, etc.

---

## 🔍 Features Used

- `danceability`
- `energy`
- `acousticness`
- `instrumentalness`
- `liveness`
- `valence`
- `tempo`

---

## 📊 Project Workflow

### 1. **Data Preprocessing**
- Removed duplicates and nulls
- Encoded categorical columns

### 2. **Exploratory Data Analysis**
- Genre distribution
- Playlist name frequency
- Distributions of audio features

### 3. **Correlation Matrix**
- Heatmap of audio feature relationships

### 4. **Clustering**
- KMeans clustering on audio features
- PCA for 2D cluster visualization

### 5. **Cluster Insights**
- Cluster vs Genre
- Cluster vs Playlist Name (Top 10 + Others)

### 6. **Recommendation System**
- Recommends songs based on similar cluster and genre

---

## 🛠 Tech Stack

| Tool | Use |
|------|-----|
| Python | Programming |
| Jupyter Notebook | Development |
| pandas, numpy | Data processing |
| seaborn, matplotlib | Visualizations |
| scikit-learn | Clustering, PCA |

