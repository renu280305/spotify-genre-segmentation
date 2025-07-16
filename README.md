<h1 align="center">🎧 Spotify Songs' Genre Segmentation</h1>

<p align="center">
  <b>Minor  Project - B.E. Computer Science and Engineering</b><br>
  Academic Year: <code>2025–2026</code> • Implemented using Python, Clustering Algorithms & Data Analysis
</p>

---

## 🧠 Objective

> 🎯 To explore and analyze the musical features of Spotify songs and segment them into clusters using unsupervised learning techniques.  
> ✅ Build a basic content-based recommendation system based on song similarity and genre grouping.

---

## 📁 Dataset Description

This project uses a Spotify song dataset containing:
- 🎶 `playlist_genre`  
- 📜 `playlist_name`  
- 🎛️ Audio-based features:  
  - `danceability`  
  - `energy`  
  - `acousticness`  
  - `instrumentalness`  
  - `liveness`  
  - `valence`  
  - `tempo`

---

## 🛠 Technologies and Libraries Used

| Tool/Library      | Purpose                          |
|-------------------|----------------------------------|
| Python            | Core programming language        |
| Jupyter Notebook  | Interactive development platform |
| pandas, numpy     | Data analysis and manipulation   |
| matplotlib, seaborn | Data visualization            |
| scikit-learn      | KMeans clustering, scaling, PCA  |

---

## 📊 Project Workflow

### 🔹 Step 1: Data Preprocessing
- Removed missing values and duplicates
- Encoded categorical variables (genres and playlist names)

### 🔹 Step 2: Exploratory Data Analysis
- Plotted genre and playlist distributions
- Visualized feature distributions and correlations

### 🔹 Step 3: Clustering with KMeans
- Scaled selected features using StandardScaler
- Applied KMeans clustering with 5 clusters
- Visualized song clusters using PCA (2D)

### 🔹 Step 4: Cluster Analysis
- Compared clusters against genres and playlist names
- Filtered top playlist names to remove overlap

### 🔹 Step 5: Recommendation Function
- Created a function to recommend songs from the same cluster and genre
- Based on input song index

---

## 📂 Project Notebook

📄 Click below to view the complete notebook containing code, outputs, visualizations, and clustering logic:

👉 [**Open Full Notebook**](./spotify_project.ipynb)

---

## 👤 Author

> **C R RENUKA**  
> Bachelor of Engineering in Computer Science and Engineering (B.E. CSE)  
>  Agni College of Technology
> Academic Year: 2025–2026

---

<p align="center">⭐ If you found this project useful, feel free to star the repository!</p>
