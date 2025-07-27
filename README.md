# 🎧 Spotify Audio Pattern Analysis Dashboard
Interactive Tableau dashboard visualizing Spotify audio trends

This Tableau project dives into Spotify’s audio features to uncover trends across genres and decades. It visualizes how song characteristics like **energy**, **danceability**, **valence**, and **tempo** vary across **genres** and over **years**, helping us understand the evolving mood and vibe of global music.

---
## 📌 Project Highlights

- 📊 Built using **Tableau Public**
- 🧼 Cleaned a large Spotify dataset  with Excel & Python
- 🧠 Visualized patterns in **energy**, **valence**, **tempo**, and **popularity**
- 🎵 Explored music **genre**, **mood over years**, and **danceability trends**
- 🚀 Deployed and documented project on **GitHub** for professional showcase

- ## 📁 Dataset Summary

- **Source**: Spotify dataset from Kaggle (derived from Spotify API)
- **Rows**: ~230,000 tracks → Cleaned down to ~114,000 entries
- **Columns**:  
  - `track_name`, `artist`, `genre`, `release_year`, `popularity`
  - Audio features: `energy`, `valence`, `danceability`, `tempo`, `loudness`, etc.
- **Size**: ~36 MB (CSV)
- **Cleaning**:
  - Removed duplicates & nulls
  - Extracted year from release dates
  - Filtered for top 50 genres
  - Final file saved as `Spotify_cleaned_dataset.csv`

## 📊 Dashboard Highlights

| Sheet Title | Description | Preview |
|-------------|-------------|---------|
| 🎨 **Genre Comparison** | Bar chart comparing average energy, valence, tempo, and popularity across music genres. | ![Genre](https://github.com/Nandini19062994/Spotify-audio-dashboard/blob/main/06%20Genre%20Comparison.png?raw=true) |
| 📅 **Mood Trend Over Years** | Line chart tracking how energy and mood (valence) of songs evolved by year. | ![Mood](https://github.com/Nandini19062994/Spotify-audio-dashboard/blob/main/07%20Mood%20Trends.png?raw=true) |
| ⚡ **Tempo Distribution** | Histogram showing how tempo is distributed across songs. | ![Tempo](https://github.com/Nandini19062994/Spotify-audio-dashboard/blob/main/08%20Tempo%20Distribution.png?raw=true) |
| 🔥 **Energy vs Popularity Scatterplot** | Color-coded scatterplot by genre revealing the relationship between a song’s energy and its popularity. | ![Scatter](https://github.com/Nandini19062994/Spotify-audio-dashboard/blob/main/05%20Energy%20vs%20Popularity%20Scatterplot%20by%20Genre.png?raw=true) |
| 💃 **Top Dance Tracks** | A ranked list of most danceable songs from the dataset with key metrics. | ![Dance](https://github.com/Nandini19062994/Spotify-audio-dashboard/blob/main/09%20Top%20Dance%20Tracks.png?raw=true) |




---

## 🧠 Insights Derived

- Genres like **edm** and **dance** have the highest average **energy** and **danceability**.
- The **valence** (musical positivity) of popular songs peaked in the early 2000s and has shown varied trends since.
- Tempo trends remain mostly consistent across decades, but outliers exist in certain genres.
- Highly danceable tracks often fall into genres like **pop**, **hip-hop**, and **electronic**.

---

## 📁 Files Included

| File                    | Description                           |
|-------------------------|---------------------------------------|
| `Spotify_Audio_Dashboard.twbx` | Tableau workbook file           |
| `spotify_dataset.csv`         | Cleaned Spotify dataset          |
| `dashboard_preview.png`       | Screenshot of the dashboard      |
| `README.md`                   | This documentation file          |

---

## 🚀 How to Explore the Dashboard

1. **Download** the `.twbx` file.
2. Open it in [Tableau Public](https://public.tableau.com).
3. Interact with filters, tooltips, and visualizations to explore music trends.

---

## 🛠 Tools & Techniques

- **Tool:** Tableau Public
- **Skills Used:** Data Cleaning, Visualization, Dashboard Design, EDA
- **Techniques:** Sorting, filtering, average/sum calculations, interactivity
- **GitHub** (for hosting & sharing)

---

## 📌 Why This Project?

As someone deeply passionate about exploring the intersection of data and storytelling, I wanted to create a project that was not only visually compelling but also insightful and relevant. Music, being a universal language, offered the perfect dataset to analyze patterns, trends, and emotions through numbers.

This project allowed me to:

- Apply **data analysis and visualization** techniques to real-world, relatable data.
- Explore how **audio features reflect changing musical trends** across time and genres.
- Design a clean, interactive **dashboard in Tableau** that can communicate insights at a glance.

By working on this project, I enhanced my **data cleaning**, **feature exploration**, and **dashboard design** skills while building something that reflects both my analytical ability and creative mindset.

It’s a perfect blend of data, design, and curiosity — which is exactly what excites me about a career in data analytics.

---

## 🌐 Author

**Nandini Rai**  
Aspiring Data Analyst | Passionate about turning numbers into narratives  
📫 Feel free to connect via 
- 📧 Email: nandinigirdharrai@gmail.com
- LinkedIn:(https://www.linkedin.com/in/nandini-rai-5b93a4272/) 

---

## 🏷 Tags

`#Tableau` `#DataVisualization` `#Spotify` `#EDA` `#BeginnerProject`
