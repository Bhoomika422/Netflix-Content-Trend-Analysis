# 🎬 Netflix Content & Trend Analysis

An exploratory data analysis project examining Netflix's movie and TV show catalog using Python, NumPy, Pandas, Matplotlib, and Seaborn to uncover content trends and insights.

---

## 📊 Project Overview
This project explores the Netflix dataset to uncover structural trends regarding content distribution, geographic production footprints, historical growth trajectories, and data cleaning workflows. It transforms raw metadata into actionable insights suitable for media analytics and business strategy.

---

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Data Manipulation & Cleaning:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Environment:** Jupyter Notebook / VS Code

---

## 📈 Key Findings & Summary Metrics
* **Catalog Composition:** Analyzed a total of **8,790** titles on Netflix, comprising **6,126** movies and **2,664** TV shows. Movies significantly outnumber TV shows, accounting for roughly **70%** of the catalog.
* **Geographic Production:** The United States and India contribute the largest share of global content production, reflecting strong local partnerships and massive target audiences.
* **Growth Trajectory:** Content additions grew exponentially over recent years, with the highest volume of additions peaking between **2019 and 2021** during Netflix's rapid global expansion phase.
* **Data Hygiene & Preprocessing:** Handled real-world data imperfections, such as addressing missing or placeholder director values (e.g., `'Not Given'`).

---

## 📉 Key Visualizations

### 1. Content Distribution (Movies vs. TV Shows)
*(A visual breakdown showing the ~70% movie dominance on the platform)*
![Content Type Distribution](content_type_distribution.png)

### 2. Top Content-Producing Countries
*(Highlighting the leading production hubs globally)*
![Top Countries](top_countries.png)

### 3. Content Growth Over Time
*(Illustrating the steep surge in platform additions leading up to 2019-2021)*
![Growth Trajectory](content_growth_trend.png)

---

## 🚀 Future Scope & Next Steps
* **Content Recommendation System:** Extend this project by applying Natural Language Processing (NLP) on the `description` and `listed_in` columns to build a Content-Based Movie/Show Recommendation System.
* **Interactive Dashboard:** Export cleaned metrics into **Power BI** or **Tableau** to build an interactive media performance dashboard.

---

## 📁 Repository Structure
```text
├── Netflix.csv                      # Raw dataset used for analysis
├── Netflix-Content-Analysis.ipynb   # Complete Jupyter Notebook with code & charts
├── README.md                        # Project documentation
└── images/                          # Saved charts and visual assets# Netflix-Content-Trend-Analysis
