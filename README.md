
# 🎧 Spotify Listening Insights Dashboard – Power BI

This repository features an interactive, custom-built **Spotify Dashboard** created using Power BI. The dashboard offers a deep dive into personal listening data, visualizing trends in music preferences, audio characteristics, and top artists/tracks through engaging and insightful visuals.

---

## 📌 Project Overview

The goal of this dashboard is to transform raw Spotify streaming data into a dynamic and visually appealing analytical tool. It helps users understand their music taste, discover patterns in listening behavior, and engage with personalized statistics in a compelling way.

---

## 🔍 Key Features

* 🎵 **Top Tracks & Artists Leaderboard** – Highlight your most played songs and artists.
* 🧠 **Audio Feature Analysis** – Visualize metrics like energy, danceability, valence, and acousticness.
* 📅 **Time-Based Listening Trends** – Explore when and how often you listen to music across days, weeks, and months.
* 🌐 **Genre Distribution** – Break down your streaming activity by genre.
* 🖼 **Album Cover Display** – Enjoy visuals of your top songs using embedded album art.
* 🧮 **KPI Cards** – Show key insights like total listening time, most streamed artist, and average song popularity.

---

## 🛠 Tools Used

* **Power BI Desktop** – For creating visuals and building data models.
* **Power Query Editor** – For cleaning, transforming, and shaping data.
* **Spotify Developer API** – For extracting streaming history and track metadata.
* **DAX (Data Analysis Expressions)** – For calculated metrics and interactivity.

---

## 🧩 Data Pipeline & Modeling

1. **Data Source**: Spotify streaming data downloaded via API or your account's data export.
2. **Data Cleaning**:

   * Removed nulls/duplicates.
   * Converted durations to minutes.
   * Parsed timestamps and extracted date parts (day, week, month).
3. **Modeling**:

   * Fact table: Track-level streaming data.
   * Dimension tables: Date, Artist, Genre.
   * Created relationships and hierarchy fields for time analysis.

---

## 📊 DAX Measures & Metrics

* `Total Listening Time` (in minutes/hours)
* `Most Streamed Track`
* `Most Streamed Artist`
* `Average Energy`, `Danceability`, `Valence`
* `Play Count` per genre, artist, year

These measures power cards, charts, and dynamic filtering interactions throughout the dashboard.

---

## 🎨 Design & UX

* Clean, glassmorphism-inspired layout with dark Spotify theme.
* Consistent color palette (green, black, white).
* Tooltips and slicers for enhanced interactivity.
* Custom visuals for album artwork.
* Responsive layout for Power BI Desktop and Service.

---

## 📷 Dashboard Preview




```md
![Spotify Dashboard Preview](![spotify dashboard1](https://github.com/user-attachments/assets/3cfdd8b8-ebbf-490b-827b-7408e231767e)
)
```

---

## 🚀 How to Use

1. Clone or download this repository.
2. Open the `.pbix` file in Power BI Desktop.
3. Connect your own Spotify data (via API or CSV).
4. Refresh the data and explore the visuals!

---

## 💡 Learnings & Highlights

* Gained hands-on experience with **data storytelling** using real-world datasets.
* Built a full Power BI report from scratch—design, modeling, and performance.
* Improved skills in **Power Query**, **data modeling**, **DAX**, and **user-centric visualization**.
* Experimented with **audio features** as analytical variables.

---

## 📬 Contact

Feel free to connect with me for feedback, collaboration, or any questions!

📧 Email: \[your email]
🔗 LinkedIn: \[your profile]
🐙 GitHub: \[your GitHub username]

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

Let me know if you'd like help adding:

* A customized banner at the top
* Sample Spotify data (anonymized)
* A linked Medium or LinkedIn post write-up

Just say the word!
