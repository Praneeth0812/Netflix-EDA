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

**Dataset:** Netflix Movies & TV Shows Dataset

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
- Genres
- Description

---

## 📊 Project Workflow

### 1. Data Loading & Inspection
- Loaded the dataset using Pandas
- Checked shape, columns, and data types
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

1. Distribution of Movies and TV Shows
2. Top countries producing Netflix content
3. Most common content ratings
4. Netflix titles released by year
5. Most common genres

### 4. Data Visualizations

The project includes the following visualizations:

- 📊 Bar Chart
- 📈 Line Chart
- 📉 Histogram
- 🔵 Scatter Plot
- 🥧 Pie Chart
- 🔥 Correlation Heatmap

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
└── NetFlix.csv
```

---

## 🚀 How to Run

1. Clone or download this repository.
2. Open `Netflix_EDA.ipynb` using Google Colab or Jupyter Notebook.
3. Upload the dataset (`NetFlix.csv`) if required.
4. Run all cells to reproduce the analysis and visualizations.

---

## 📌 Results

The analysis revealed:

- Movies are more common than TV Shows.
- Netflix experienced rapid content growth after 2015.
- Most movies have durations between 80 and 120 minutes.
- TV-MA is the most common content rating.
- Movie duration has only a weak relationship with release year.

---
