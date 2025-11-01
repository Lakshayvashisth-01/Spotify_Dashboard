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

## 🌟 Dashboard Highlights

### 🎧 1. **Playback Simulation Panel**
- **Feature**: Displays the currently playing song with album art, title, artist, and playback controls.
- **Example**: “MAMIII” by Becky G & KAROL G or “It Goes Like Nanana” by Peggy Gou shown with a play/pause button and duration bar.
- **Purpose**: Adds realism and user engagement, mimicking the Spotify interface.

---

### 📊 2. **Core Metrics Panel**
- **Feature**: Key performance indicators (KPIs) summarizing the dataset.
- **Examples**:
  - **Total Songs**: 452
  - **Total Artists**: 214
  - **Average Song Length**: 89.46 seconds
  - **Average Popularity**: 53.6
- **Purpose**: Provides a quick snapshot of the user's music library and listening behavior.

---

### 🏆 3. **Top Songs & Artists**
- **Feature**: Lists the most played songs and frequently appearing artists.
- **Examples**:
  - Top Songs: “It Goes Like Nanana”, “16 CARRIAGES”, “I Remember Everything”
  - Top Artists: Peggy Gou, Beyoncé, Zach Bryan, Charli XCX
- **Purpose**: Highlights user preferences and listening trends.

---

### 📈 4. **Song Distribution by Artist**
- **Feature**: Bar chart showing how many songs each artist contributes.
- **Example**: Ariana Grande appears with 2 songs, others with 1 each.
- **Purpose**: Reveals artist dominance and diversity in the playlist.

---

### 🧩 5. **Album Type Breakdown**
- **Feature**: Pie chart showing song distribution by album type.
- **Examples**:
  - Singles: 91%
  - Albums: 9%
- **Purpose**: Indicates whether the user prefers quick releases or full-length albums.

---

### 🔞 6. **Explicit vs Non-Explicit Content**
- **Feature**: Pie chart comparing explicit and clean songs.
- **Examples**:
  - Explicit: 18%
  - Non-Explicit: 82%
- **Purpose**: Useful for content filtering or understanding lyrical preferences.

---

### 📊 7. **Popularity Analysis**
- **Feature**: Bar chart showing average popularity by album type.
- **Examples**:
  - Singles: ~80
  - Albums: ~70
- **Purpose**: Evaluates how different formats perform in terms of popularity.

---

### 📅 8. **Monthly & Quarterly Trends**
- **Feature**: Line and bar charts showing average popularity and distinct song counts over time.
- **Examples**:
  - May has the highest distinct song count.
  - Popularity trends fluctuate between March and April.
- **Purpose**: Tracks listening habits and new song additions across months or quarters.

---

### 📆 9. **Songs by Year**
- **Feature**: Bar chart showing song distribution by release year.
- **Example**: 2023 has the highest number of songs.
- **Purpose**: Reveals whether the user prefers newer or older music.

---

### 📐 10. **Data Model Integration**
- **Feature**: Fields like `Song`, `Artist`, `Album Type`, `Popularity`, `Play Count`, `Month`, `Year` are used for slicing and filtering.
- **Purpose**: Enables dynamic filtering and deeper analysis.

---

## ✅ Summary of Benefits
- **Interactive**: Users can explore trends with slicers and toggles.
- **Visual**: Clean layout with Spotify branding and album art.
- **Insightful**: Combines personal listening data with analytical depth.
- **Customizable**: Easily adaptable to other datasets or themes.

Would you like a matching slide or infographic summarizing these features for presentation or documentation?

---

## 📂 Folder Structure
```
Spotify-Dashboard/
│
├── Dataset/
│   └── spotify_data.csv
│
├── Dashboard/
│   └── Spotify.pbix
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
