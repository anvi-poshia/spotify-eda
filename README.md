# 🎵 Spotify Tracks — Exploratory Data Analysis

![Python](https://img.shields.io/badge/Python-3572A5?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-130654?style=flat&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4c72b0?style=flat)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

An end-to-end exploratory data analysis of **114,000 Spotify tracks** across **114 genres**, uncovering what makes a song popular and how audio features relate to each other.

---

## 📌 Key Findings

- 🔹 **Viral success is rare** — nearly 20,000 songs have zero popularity; most tracks are never discovered
- 🔹 **Pop-film & K-pop dominate** — soundtrack songs and K-pop outperform all other genres in average popularity
- 🔹 **Energy & loudness move together** — strongest positive correlation at 0.76
- 🔹 **Acoustic = low energy** — energy and acousticness have a -0.73 correlation
- 🔹 **No single feature predicts popularity** — all audio features have near-zero correlation with popularity score

---

## 📊 Visualizations

| Chart | Insight |
|-------|---------|
| Popularity Distribution | Right-skewed — most songs cluster at low popularity |
| Top 10 Genres by Popularity | Pop-film #1, K-pop #2, mood genres beat mainstream pop |
| Audio Feature Correlation Heatmap | Energy/loudness correlated; acousticness inversely tied to energy |
| Energy vs Acousticness Scatter | Clear negative trend — two distinct song clusters emerge |

---

## 🛠️ Tech Stack

Python · Pandas · NumPy · Matplotlib · Seaborn · Jupyter Notebook

---

## 📁 Project Structure

```
spotify-eda/
├── spotify_eda.ipynb   # Main analysis notebook
└── README.md           # Project overview
```

---

## ▶️ How to Run

1. Clone this repo
2. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset) and place `dataset.csv` in the root folder
3. Open `spotify_eda.ipynb` in Jupyter or VS Code and run all cells

```bash
git clone https://github.com/anvi-poshia/spotify-eda.git
cd spotify-eda
jupyter notebook spotify_eda.ipynb
```

---

## 👤 Author

**Anvi Poshia** — MS CS @ UMass Amherst  
[GitHub](https://github.com/anvi-poshia) · [LinkedIn](https://linkedin.com/in/anvi-poshia)