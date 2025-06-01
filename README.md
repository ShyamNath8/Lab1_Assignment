Name: Shyam Nath
Course Title: Advanced Big Data and Data Mining (MSCS-634-M40) 
Assignment Title: Lab 1: Data Visualization, Data Preprocessing, and Statistical Analysis Using Python in Jupyter Notebook

Dataset Used:
Superstore Sales Dataset (`superstore.csv`)

---

Purpose of the Lab

The purpose of this lab is to apply foundational data science techniques in Python using Jupyter Notebook. The tasks include:
- Data loading and exploration
- Visualizing trends and distributions
- Cleaning and pre-processing the data
- Detecting and handling missing values and outliers
- Reducing and scaling data
- Performing descriptive and statistical analysis

---
Key Tasks Performed

Step 1: Data Collection
- Loaded the `superstore.csv` dataset using `pandas`.
- Displayed the first five rows of the dataset for review.

Step 2: Data Visualization
- Bar Chart was used to compare total sales across different regions.
- Scatter Plot was used to examine the spread and outliers in the `Profit` column.

Step 3: Data Pre-processing
- Handling Missing Values: Checked for missing values — none were found in the dataset.
- Outlier Detection: Outliers in the `Profit` column were detected using the IQR method and removed.
- Data Reduction:
  - A 30% random sample of the dataset was created.
  - Irrelevant columns such as `Row ID`, `Customer Name`, and `Product Name` were dropped.
- Data Scaling: Applied Min-Max Scaling to `Sales` and `Profit` columns and compared values before and after scaling.

Step 4: Statistical Analysis
- Used `.info()` and `.describe()` to inspect structure and summary statistics.
- Calculated measures of central tendency: **min, max, mean, median, mode**.
- Calculated dispersion: **range, quartiles, IQR, variance, standard deviation**.
- Generated a **correlation matrix** to study relationships between numerical features.

---

Key Insights

- The West region had the highest sales in the dataset.
- The `Profit` column contained significant **outliers**, mostly from extreme losses.
- After scaling, both `Sales` and `Profit` were normalized to a range between 0 and 1.
- A strong **positive correlation** was found between `Sales` and `Profit`, but not with `Discount`.

---

Challenges Faced

- No missing values or obvious issues with the dataset required modification, so artificial examples were not created.
- Outlier handling required careful filtering to ensure the main structure of the data remained valid.
- Data reduction required judgment on which columns were non-essential without affecting the analysis.

---

Repository Contents
-Lab1_Shyam          # The Jupyter Notebook File
-superstore.csv      # The dataset used for Analysis
-Screenshots         # The screenshots showing analysis of each project step
-README File
