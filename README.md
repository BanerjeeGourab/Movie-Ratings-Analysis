# 🎬 Movie Ratings Analysis Using Python

## 📌 Project Overview

This project focuses on analyzing movie data using Python and its popular data analysis libraries: **NumPy, Pandas, and Matplotlib**. The objective is to explore movie ratings, identify trends across genres and directors, analyze rating patterns over time, and investigate relationships between movie budgets, revenue, and ratings.

## 🎯 Project Objectives

- Load and inspect movie data using Pandas.
- Identify and handle missing values.
- Calculate mean, median, and standard deviation using NumPy.
- Analyze average ratings by genre and director.
- Explore movie rating trends over different years.
- Visualize relationships between budget, revenue, and ratings.
- Identify the top 10 highest-rated movies.

## 🛠️ Technologies Used

- **Python** – Programming language
- **NumPy** – Numerical computations and statistical analysis
- **Pandas** – Data manipulation and cleaning
- **Matplotlib** – Data visualization
- **Google Colab / Jupyter Notebook** – Development environment

## 📂 Project Structure

```text
Movie-Ratings-Analysis/
│
├── README.md
├── Project_2_Movie_Ratings_Analysis_Using_NumPy,_Pandas,_and_Matplotlib.ipynb
└── movie_ratings_analysis_dataset.csv
```

## 📊 Dataset Description

The dataset contains movie information, including ratings, genres, directors, release years, budgets, revenue, runtime, and vote counts.

| Column | Description |
|---|---|
| Movie | Movie title |
| Genre | Movie genre |
| Director | Movie director |
| Year | Release year |
| Rating | Movie rating |
| Budget_Million | Movie budget in millions |
| Revenue_Million | Movie revenue in millions |
| Runtime_Minutes | Movie runtime in minutes |
| Votes_Million | Number of votes in millions |

## 🔍 Project Workflow

### 1. Data Loading and Inspection

- Imported the dataset using Pandas.
- Viewed the first few rows of the dataset.
- Checked column names, data types, and dataset information.
- Identified missing values.

### 2. Data Cleaning

- Handled missing values in numerical columns.
- Used column means to fill missing numerical values.
- Verified the cleaned dataset.

### 3. Statistical Analysis Using NumPy

Calculated:

- Mean of movie ratings, budgets, and revenue.
- Median of movie ratings, budgets, and revenue.
- Standard deviation of movie ratings, budgets, and revenue.

### 4. Data Analysis Using Pandas

- Calculated average ratings by genre.
- Compared average ratings by director.
- Analyzed average ratings across release years.

### 5. Data Visualization Using Matplotlib

Created visualizations to understand the dataset:

- Bar chart of average ratings by genre.
- Bar chart of average ratings by director.
- Line chart showing rating trends over the years.
- Scatter plot of budget versus rating.
- Scatter plot of revenue versus rating.
- Horizontal bar chart showing the top 10 highest-rated movies.

## 💡 Key Questions Explored

- Which genres have the highest average ratings?
- Which directors have the highest average ratings?
- How do movie ratings change over time?
- Is there a relationship between movie budget and rating?
- Is there a relationship between movie revenue and rating?
- Which movies have the highest ratings in the dataset?

## ▶️ How to Run the Project

### Using Google Colab

1. Open the project notebook in Google Colab.
2. Upload the CSV dataset.
3. Ensure the dataset filename matches the filename specified in the notebook.
4. Run the notebook cells sequentially.
5. Review the statistical results and visualizations.

### Running Locally

Install the required libraries:

```bash
pip install numpy pandas matplotlib jupyter
```

Load the dataset using Pandas:

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt

data = pd.read_csv("movie_ratings_analysis_dataset.csv")

print(data.head())
print(data.info())
print(data.isnull().sum())
```

Open the `.ipynb` file in Jupyter Notebook or JupyterLab and execute the cells.

## 📈 Skills Demonstrated

- Python programming
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Statistical analysis using NumPy
- Data manipulation using Pandas
- Data visualization using Matplotlib
- Grouping and aggregation
- Trend analysis and interpretation

## 🔮 Future Improvements

- Perform correlation analysis between numerical variables.
- Investigate relationships between runtime, votes, and ratings.
- Explore outliers in budget and revenue.
- Add interactive visualizations using Plotly.
- Build an interactive dashboard for movie data analysis.

## 👨‍💻 Author

**Gourab Banerjee**

---

⭐ If you find this project useful, feel free to explore the repository.

