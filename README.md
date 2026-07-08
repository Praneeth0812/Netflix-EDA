# 📊 Exploratory Data Analysis on Netflix Movies & TV Shows Dataset

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the **Netflix Movies & TV Shows Dataset** using Python. The objective is to inspect, clean, analyze, and visualize the data to identify meaningful trends and patterns. Based on the analysis, business insights and recommendations are provided.

---

## 🎯 Objectives

- Load and inspect the dataset
- Clean missing and duplicate data
- Perform Exploratory Data Analysis (EDA)
- Create meaningful visualizations
- Generate business insights and recommendations

---

## 🛠️ Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

---

## 📂 Dataset

**Dataset:** Netflix Movies & TV Shows Dataset (`netflix_titles.csv`)

The dataset contains information about Netflix titles, including:

- Show ID
- Type (Movie / TV Show)
- Title
- Director
- Cast
- Country
- Date Added
- Release Year
- Rating
- Duration
- Listed In (Genres)
- Description

---

## 📊 Project Workflow

### 1. Data Loading & Inspection
- Loaded the dataset using Pandas
- Checked dataset shape, columns, and data types
- Identified missing values
- Checked duplicate records

### 2. Data Cleaning
- Filled missing values in:
  - Director
  - Cast
  - Country
  - Rating
- Removed rows with missing `date_added`
- Removed duplicate records

### 3. Exploratory Data Analysis (EDA)

The following questions were answered:

1. What is the distribution of Movies and TV Shows?
2. Which countries have the highest number of Netflix titles?
3. Which content ratings are most common?
4. How has Netflix content changed over the years?
5. What are the most common content categories (Listed In)?

### 4. Data Visualizations

The project includes the following visualizations:

- 📊 Bar Chart
- 📈 Line Chart
- 📉 Histogram
- 🔵 Scatter Plot
- 🥧 Pie Chart
- 🔥 Heatmap

### 5. Insights & Recommendations

The notebook concludes with:

- Five business insights
- Five business recommendations
- Most surprising finding
- Conclusion

---

## 📁 Repository Contents

```text
Netflix-EDA/
│
├── Netflix_EDA.ipynb
├── README.md
└── netflix_titles.csv
```

---

## 🚀 How to Run

1. Clone or download this repository.
2. Open `Netflix_EDA.ipynb` using Google Colab or Jupyter Notebook.
3. Upload the dataset (`netflix_titles.csv`) if required.
4. Run all cells to reproduce the analysis and visualizations.

---

## 📌 Results

The analysis revealed the following key findings:

- Movies constitute a larger portion of Netflix's catalog than TV Shows.
- Netflix experienced significant content growth after 2015.
- Most movies have durations between 80 and 120 minutes.
- TV-MA and TV-14 are among the most common content ratings.
- Drama, International Movies, and Comedy are among the most represented content categories.

---
