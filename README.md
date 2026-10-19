# 🎵 Spotify Top 50 World — Power BI Dashboard

## 📌 Project Overview

The **Spotify Top 50 World Dashboard** is a data analytics project created using Microsoft Power BI to explore and analyze Spotify's global Top 50 music chart data.

The dashboard transforms raw Spotify data into interactive visualizations, helping users understand song popularity, artist performance, album distribution, track duration, and music trends over time.

## 🎯 Project Objectives

- Analyze the popularity of songs in the Spotify Top 50 World chart.
- Explore artists, albums, and track information.
- Understand music trends across different dates and years.
- Compare explicit and non-explicit tracks.
- Present key insights through an interactive Power BI dashboard.

## 🛠️ Tools & Technologies

- **Microsoft Power BI** — Data visualization and dashboard development
- **Power Query** — Data cleaning and transformation
- **DAX** — Calculated columns and measures
- **CSV** — Dataset storage and input
- **GitHub** — Project hosting and version control

## 📂 Dataset Description

The project uses the `spotify-top-50-world.csv` dataset.

The dataset contains the following fields:

| Column | Description |
|---|---|
| `date` | Date of the chart record |
| `position` | Song's chart position |
| `song` | Name of the song |
| `artist` | Artist or artists |
| `popularity` | Spotify popularity score |
| `duration_ms` | Track duration in milliseconds |
| `album_type` | Album release type |
| `total_tracks` | Number of tracks in the album or release |
| `release_date` | Release date of the album or track |
| `is_explicit` | Indicates whether a track is explicit |
| `album_cover_url` | URL of the album cover image |

## 📊 Dashboard Features

The dashboard focuses on music analytics through KPI cards, charts, and other visual elements.

- **Total Album Count:** Overview of album-related data.
- **Average Popularity:** Insights into the popularity of tracks.
- **Average Track Duration:** Analysis of song lengths.
- **Popularity Trends:** Explore popularity across different years.
- **Track Duration Trends:** Compare average song duration over time.
- **Explicit vs. Non-Explicit Tracks:** Understand the distribution of explicit content.
- **Album and Artist Analysis:** Explore artist and album-related information.
- **Interactive Visualizations:** Use chart interactions and filters to explore the data.

*Note: The listed features describe the project's intended analysis. The visuals and measures available depend on the final dashboard implementation.*

## ⚙️ Project Workflow

1. **Data Collection:** Imported the Spotify Top 50 World CSV dataset.
2. **Data Cleaning:** Used Power Query to inspect data types and prepare the dataset for analysis.
3. **Data Transformation:** Prepared date, duration, album, artist, and popularity fields for visualization.
4. **Data Modeling:** Organized the data for reporting and analysis.
5. **DAX Calculations:** Created measures and calculated columns for key metrics and trends.
6. **Dashboard Development:** Built charts, KPI cards, and interactive visualizations in Power BI.
7. **Insights & Analysis:** Used the dashboard to explore patterns in Spotify chart data.

## 🚀 How to Use This Project

1. Clone or download this repository.
2. Ensure that Microsoft Power BI Desktop is installed.
3. Open `spotify_powerbi.pbix` in Power BI Desktop.
4. If prompted, update the CSV data source path to the location of `spotify-top-50-world.csv`.
5. Refresh the dataset if required.
6. Explore the dashboard using its charts, filters, and interactive elements.

## 📁 Repository Structure

```text
Spotify-Top-50-World-PowerBI/
│
├── spotify_powerbi.pbix
├── spotify-top-50-world.csv
└── README.md
```

## 💡 Key Learnings

Through this project, I gained practical experience in:

- Importing and transforming datasets using Power Query.
- Creating DAX measures and calculated columns.
- Designing interactive dashboards in Power BI.
- Working with music-related data and KPIs.
- Presenting analytical information through data visualization.
- Managing and documenting a data analytics project using GitHub.

## 🔮 Future Improvements

- Add more detailed artist and genre analysis where the required data is available.
- Improve dashboard design and user experience.
- Add advanced filtering and drill-through features.
- Explore additional relationships between popularity, track duration, and chart position.

## 👩‍💻 Author

**Adeeba Abdul Vahid**

Computer Science Engineering Student | Aspiring Data Analyst

Interested in data analytics, business intelligence, and data visualization.

---

⭐ If you find this project interesting, feel free to explore the repository!
