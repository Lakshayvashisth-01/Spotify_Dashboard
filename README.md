# Spotify_Dashboard
---

# 🎧 Spotify Dashboard

## 📌 Project Overview
The **Spotify Dashboard** is a dynamic and visually engaging Power BI project that analyzes music listening habits using Spotify data. It transforms raw song metadata into actionable insights through interactive charts, KPIs, and playback visuals. This dashboard is designed for music enthusiasts, data analysts, and developers who want to explore trends in song popularity, artist performance, and listening behavior over time.

---

## 📊 Description
This Power BI dashboard leverages Spotify streaming data to provide a comprehensive overview of user preferences and music analytics. It includes metrics such as total songs, artists, average popularity, and song duration, while also offering breakdowns by album type, explicit content, and monthly trends.

The dashboard is divided into intuitive panels that simulate a Spotify-like interface, complete with album artwork, playback controls, and real-time song highlights. It is ideal for showcasing how business intelligence tools can be applied to entertainment data for personal or professional use.

---

## 🚀 Key Features

### 🎵 Playback Simulation
- Displays the currently playing song with album art, title, artist, and duration.
- Interactive play/pause controls for aesthetic realism.

### 📈 Core Metrics
- **Total Songs**: Tracks the number of songs in the dataset.
- **Total Artists & Albums**: Measures diversity in listening habits.
- **Average Song Length**: Indicates typical duration preferences.
- **Average Popularity**: Reflects overall song appeal based on Spotify’s popularity index.

### 🧠 Song Insights
- **Top Songs by Play Count**: Highlights the most frequently played tracks.
- **Top Artists**: Identifies artists with the highest song counts or popularity.

### 📊 Visual Analytics
- **Song by Artist**: Bar chart showing song distribution across artists.
- **Song by Album Type**: Pie chart categorizing songs as Singles, EPs, or Albums.
- **Explicit vs Non-Explicit**: Pie chart comparing content types.
- **Average Popularity by Album Type**: Bar chart comparing popularity across album formats.
- **Average Popularity by Month/Quarter**: Line graph showing temporal trends.
- **Distinct Songs by Month**: Bar chart tracking new song additions over time.
- **Songs by Year**: Historical distribution of songs.

### 📁 Data Model
- Fields used include:
  - `Song`, `Artist`, `Album Type`, `Duration (hr)`, `Explicit`, `Play Count`, `Popularity`, `Month`, `Year`
- Cleaned and transformed using Power BI’s data modeling tools for optimal performance.

---

## 🛠️ Tools & Technologies
- **Power BI Desktop**: For dashboard creation and visualization.
- **Spotify Dataset**: Exported from user library or Spotify API.
- **DAX & Power Query**: Used for data transformation and calculated metrics.

---

## 📂 Folder Structure
```
Spotify-Dashboard/
│
├── Dataset/
│   └── spotify_data.csv
│
├── Dashboard/
│   └── SpotifyDashboard.pbix
│
├── Images/
│   └── dashboard_preview.png
│
└── README.md
```

---

## 📸 Preview
> ![Dashboard Preview](Images/dashboard_preview.png)

---

## 📌 How to Use
1. Clone the repository.
2. Open `SpotifyDashboard.pbix` in Power BI Desktop.
3. Replace the dataset with your own Spotify data (optional).
4. Explore the dashboard and interact with filters and visuals.

---

## 📬 Feedback & Contributions
Feel free to fork the repo, raise issues, or submit pull requests for improvements. Whether you're adding new visualizations or optimizing performance, contributions are welcome!

---
