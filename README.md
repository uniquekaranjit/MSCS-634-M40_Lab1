# MSCS-634-M40_Lab1
# Data Analysis and Preprocessing Lab

## Student: Unique Karanjit
Course Title: Advanced Big Data and Data Mining (MSCS-634-M40)   
Lab Assignment: Data Visualization, Preprocessing, and Statistical Analysis  

---

## Purpose of the Lab

The purpose of this lab was to apply core data science techniques including data collection, visualization, preprocessing, and statistical analysis using Python and Jupyter Notebook. This hands-on experience helps reinforce how to handle real-world datasets and prepare them for further analysis or machine learning workflows.

---

## Key Insights

- **Data Visualization**:
  - A bar chart comparing electric vehicle counts by **Make** revealed that Tesla dominates the dataset.
  - A histogram of **Electric Range** showed that most vehicles fall into the lower-to-medium range categories, with a few offering significantly higher ranges.

- **Data Preprocessing**:
  - Missing values were found in several columns including `Electric Range`, and were handled using mean imputation.
  - Outliers in `Base MSRP` were identified and removed using the IQR method to improve data reliability.
  - The dataset was reduced by dropping non-essential columns and applying a sample to improve computational efficiency.
  - `Base MSRP` was scaled using Min-Max scaling, and `Electric Range` was discretized into four meaningful categories (Short, Medium, Long, Very Long).

- **Statistical Analysis**:
  - Summary statistics revealed the wide price variation in electric vehicles, with the mean MSRP around $45,000.
  - Correlation analysis showed a moderate positive correlation between `Electric Range` and `Base MSRP`, implying higher range vehicles tend to be more expensive.

---

## Challenges and Decisions

- Some rows had missing or malformed values which required careful treatment to avoid skewing the analysis.
- Choosing meaningful bin edges for discretizing `Electric Range` involved examining the data distribution manually.
- Several columns such as `Vehicle Location` or `DOL Vehicle ID` were dropped as they did not contribute to the analysis goals.
- Visualizing a large number of categories (e.g., vehicle models) made charts cluttered, so focus was placed on top entries only.

---

## Tools Used

- **Pandas** for data handling and preprocessing  
- **Matplotlib & Seaborn** for data visualization  
- **NumPy** and **SciPy** for statistical measures  
- **scikit-learn** for scaling  

---

## 📂 Dataset Information

- Dataset: Electric_Vehicle_Population_Data.csv
- Source: Data.gov

---

