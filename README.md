# ODI Cricket Web Scraping and Exploratory Data Analysis

## 📌 Project Overview

This project focuses on collecting ODI cricket batting statistics through web scraping and performing data cleaning and Exploratory Data Analysis (EDA) using Python.

The data is collected from ESPN Cricinfo and contains ODI batting statistics of cricket players.

The project is divided into two main stages:

1. Web Scraping
2. Data Cleaning and Exploratory Data Analysis

---

## 🎯 Project Objectives

* Scrape ODI cricket batting statistics from ESPN Cricinfo.
* Collect and store the scraped data in a structured format.
* Clean and prepare the data for analysis.
* Handle duplicate and missing records.
* Transform and organize the dataset.
* Analyze ODI player batting performance.
* Compare player statistics across countries.
* Identify relationships between important batting metrics.
* Create meaningful visualizations and insights.

---

## 🌐 Data Collection

The ODI cricket batting data was collected using web scraping techniques.

### Libraries Used for Scraping

* Python
* Requests
* BeautifulSoup
* Pandas
* NumPy
* Regular Expressions

The scraping process collects batting statistics from multiple pages and combines the collected information into a single dataset.

---

## 📊 Dataset

The dataset contains ODI batting performance information.

### Main Columns

| Column          | Description                                              |
| --------------- | ---------------------------------------------------------|
| Player_Name     | Name of the cricket player                               |
| Country         | Country represented by the player                        |
| Start_Year      | Starting year of the player's ODI career                 |
| End_Year        | Ending year of the player's ODI career                    |
| Matches         | Number of ODI matches played                              |
| Innings         | Number of batting innings                                 |
| Not_Out         | Number of innings in which the player remained not out    |
| Total_Runs      | Total ODI runs scored                                     |
| Highest_Score   | Highest individual ODI score                               |
| Batting_Average | Batting average                                            |
| Ball_Faced      | Total balls faced                                          |
| Strike_Rate     | Batting strike rate                                        |
| 100's           | Number of centuries                                        |
| 50's            | Number of half-centuries                                   |

---

## 🧹 Data Cleaning

The scraped data was cleaned and prepared before performing analysis.

The following operations were performed:

* Checked the dataset structure.
* Removed unnecessary columns.
* Checked duplicate records.
* Removed duplicate records.
* Checked missing values.
* Removed rows with missing values.
* Reset the DataFrame index.
* Renamed columns for better readability.
* Split the `Span` column into `Start_Year` and `End_Year`.
* Removed `*` from the `Highest_Score` column.
* Extracted country information.
* Converted country codes into country names.
* Converted numerical columns into appropriate data types.
* Rearranged the columns.

---

## 📈 Exploratory Data Analysis

The cleaned dataset was analyzed using different types of analysis.

### Univariate Analysis

The following variables were analyzed individually:

* Total Runs
* Country
* Batting Average
* Strike Rate

### Bivariate Analysis

Relationships and comparisons were analyzed between:

* Matches and Total Runs
* Balls Faced and Total Runs
* Country and Batting Average
* Country and Total Runs

### Multivariate Analysis

A correlation heatmap was used to analyze relationships between:

* Total Runs
* Batting Average
* Strike Rate
* Matches
* Centuries

---

## 📊 Data Visualization

The project uses different visualization techniques, including:

* Histograms
* Count Plots
* Bar Charts
* Scatter Plots
* Correlation Heatmap

These visualizations help understand player performance and relationships between different batting statistics.

---

## 🔍 Key Insights

The analysis provides insights into:

* Distribution of ODI players based on total runs.
* Distribution of batting averages.
* Distribution of batting strike rates.
* Number of players from different countries.
* Relationship between matches and total runs.
* Relationship between balls faced and total runs.
* Comparison of batting performance across countries.
* Relationships between important batting performance metrics.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Requests
* BeautifulSoup
* Regular Expressions
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 📁 Repository Contents

```text
odi-cricket-web-scraping-eda/
│
├── 01_ODI_Cricket_Web_Scraping.ipynb
├── 02_ODI_Cricket_Data_Cleaning_EDA.ipynb
├── players_stats_raw.csv
├── players_stats_cleaned.csv
├── README.md
└── .gitignore
```

---

## ⚠️ Limitations

* The project collects data from multiple pages of the source website.
* Web-scraped data can change when the source website changes.
* Some historical player records may contain different country or team representations.
* Missing records were removed during the data-cleaning process.

---

## 👨‍💻 Author

**Lokesh Narkhede**

B.Tech — Electronics & Telecommunication Engineering

### Skills Demonstrated

* Web Scraping
* Python
* Data Cleaning
* Pandas
* Exploratory Data Analysis
* Data Visualization
* Statistical Analysis
