# 🎧 Spotify Top 1000 Tracks Analysis

This project explores the **Top 1000 Most Played Spotify Songs of All Time**, analyzing trends in popularity, sentiment, artist dominance, and album performance.

## 📂 Dataset
- **Source**: [Kaggle - Top 1000 Spotify Songs](https://www.kaggle.com/datasets/kunalgp/top-1000-most-played-spotify-songs-of-all-time?resource=download)
- Fields: `track_name`, `artist`, `album`, `release_date`, `popularity`, `duration_min`, `spotify_url`

## 🛠️ Libraries Used
- `pandas`, `matplotlib`, `seaborn` – Data wrangling & visualization  
- `vaderSentiment` – Sentiment scoring for track titles  
- `wordcloud` – Sentiment-based word clouds  
- `nbformat` – Notebook parsing

## 📊 Project Highlights
- Most tracks range from **2.5–4 minutes** long  
- Artists like **The Weeknd** and **Drake** dominate in frequency  
- Positive sentiment track titles are slightly more popular  
- Albums like *Starboy* and *Dreamland* include multiple top tracks  
- Release spikes observed post-2015, with early 2025 maintaining momentum

## ⚠️ Challenges Faced
- Missing release dates: handled via `pd.to_datetime` with `errors='coerce'`  
- Seaborn palette deprecation warnings: fixed by using built-in palettes  
- Inconsistent month display in heatmaps: resolved via dynamic filtering

## ✅ Recommendations
- Prioritize song durations between 2.5–4 mins for mass appeal  
- Promote tracks with **positive sentiment** in ads and playlists  
- Target Q1 (Jan–Mar) releases for visibility and early-year attention  
- Consider sentiment and artist when curating themed playlists

## 🚀 Next Steps
- Integrate Spotify API to analyze genre, streams & user locations  
- Add audio features like `energy`, `valence`, and `tempo`  
- Compare trends with other platforms (Apple Music, YouTube)

---

> 🔎 *Notebook:* `SPORTIFY_ANALYSIS.ipynb`  
> ✍️ *Author:* Nwaukwa Gracious | April 2025  
