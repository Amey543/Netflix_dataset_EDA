# 📊 Netflix Movies and TV Shows - Exploratory Data Analysis (EDA)

This project explores and analyzes a dataset of Netflix Movies and TV Shows to extract valuable insights using data cleaning, visualization, and summary statistics.

---

## 🔧 Data Cleaning & Missing Value Handling

### 🧩 Percentage of Missing Data

| Column         | % Missing |
|----------------|-----------|
| show_id        | 0.000%    |
| type           | 0.000%    |
| title          | 0.000%    |
| director       | 29.91%    |
| cast           | 9.37%     |
| country        | 9.44%     |
| date_added     | 0.11%     |
| release_year   | 0.000%    |
| rating         | 0.05%     |
| duration       | 0.03%     |
| listed_in      | 0.000%    |
| description    | 0.000%    |

### ✅ Handling Strategy

- Missing values in **director**, **cast**, and **country** columns were filled with:  
  `column_name_Unknown`
- Rows with missing data in **date_added**, **rating**, or **duration** were dropped.

---

## 📈 Key Insights from the Dataset

### 🎬 Content Type Distribution
- **Movies:** 6,126 entries (69.7%)
- **TV Shows:** 2,664 entries (30.3%)

### 📅 Monthly Additions
- **Fewest additions:** February and May  
- **Most additions:** July and December

### 🕰️ Release Year Trends
- **Most releases:** 2018, followed by 2017  
- **Fewest releases:** 2012 and 2013

### 🎞️ Ratings Distribution
- **Most common rating:** TV-MA  
- **Second most:** TV-14  
- **Least common ratings:** NC-17 and UR

### 🎭 Genre Popularity
- **Top genre:** International Movies  
- **Followed by:** Drama and Comedy  
- **Least popular genre:** Romantic Movies

### 🧑‍🎓 Top Contributors
- **Most movies directed by:** Rajiv Chilaka  
- **Most appearances by actor:** Anupam Kher

---

## 📁 Dataset Information

> This dataset contains details about shows available on Netflix including:
- Title
- Type (Movie/TV Show)
- Director and Cast
- Country of production
- Date added to Netflix
- Release year
- Rating
- Duration
- Genre (Listed In)
- Description

---

## 📌 Project Status

✅ Initial analysis complete  
📊 More visualizations and deep-dives coming soon...

---

## 🚀 Tools Used

- Python
- Pandas
- Matplotlib / Seaborn
- Jupyter Notebook

---

## 📬 Contact

For any questions or suggestions, feel free to reach out.


