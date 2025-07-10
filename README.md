# Spotify-Analysis-using-PowerBI
## 🎧 Spotify Trends Analysis

A comprehensive Power BI dashboard that analyzes user listening patterns on Spotify using historical streaming data. This project aims to uncover behavioral trends in music consumption and deliver actionable insights into user preferences, content engagement, and listening diversity.

---

###  Objective

To analyze Spotify user behavior by transforming streaming data into meaningful insights that support smarter content curation, marketing strategies, and user engagement decisions.

---

###  Dataset
- **Source**: Spotify listening history till 2024 (exported in `.csv` format)
- **Contents**: Timestamps, album names, artist names, track names, durations
- **Rows**: Thousands of records representing music played over multiple years
- **Data Coverage**: Track, artist, album, and time-based information

---

###  Tools Used

- **Power BI** (for data modeling, DAX, and dashboard development)
- **DAX Measures** (Year-over-Year growth, cumulative totals, top N logic)
- **Power Query** (for cleaning and transforming raw data)

---

###  Key Features & Metrics

- **YOY Analysis**: Compare latest year vs previous year play counts across tracks, albums, and artists
- **Listening Patterns**:
  - Weekday vs Weekend behavior
  - Hourly heat map of listening times
- **Top 5 Analysis**: Most played artists, albums, and tracks
- **Quadrant Analysis** (Scatter Plot):
  - Categorizes songs into 4 groups based on frequency and average duration:
    -  High frequency + long duration
    -  Low frequency + long duration
    -  High frequency + short duration
    -  Low frequency + short duration
- **Dynamic Filters and Slicers**: Allowing users to segment data by year, time, and music type
- **Custom DAX Calculations**:
  - `YoY Growth %`
  - `Latest Year vs Previous Year`
  - Measures for top performers and distribution

---

###  Dashboard Previews

Spotify Overview - ![SP_D1](https://github.com/user-attachments/assets/216b93c4-91af-413e-87d4-3d42052164d5)
Listening Pattern - ![SP_D2](https://github.com/user-attachments/assets/c19aa537-8ec1-4360-8eeb-46063cb5bea9)
Details - ![SP_D3](https://github.com/user-attachments/assets/6534f85f-d349-4bfc-8866-0970448d0cac)


Drive Link *(for pdf)* - https://drive.google.com/open?id=1sgwMAB2jf1lfOi9kEEMCghV8Ab0ufktU&usp=drive_fs

Drive Link *(for .pbix file)* - https://drive.google.com/open?id=1IWJ7_Fj5VNrt-XqXiwUTWUGr3Q1WrEjy&usp=drive_fs
* tip - Read how to run below*

---

###  Key Insights

- Most users prefer specific albums during weekends, while artist diversity increases on weekdays.
- Peak listening occurs during late evenings (around 8–10 PM).
- A small group of high-engagement tracks accounts for a large portion of total listening time.
- YOY engagement with albums decreased slightly, while track diversity increased.

---

###  How to Run

1. Download the `.pbix` file from this repo.
2. Open using **Power BI Desktop** (latest version recommended).
3. Use filters to explore yearly comparisons, top performers, and pattern trends.
4. No external credentials or APIs required — dataset is included.

---
