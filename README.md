# ☕ Starbucks Beverage Nutrition Analysis | Python

## 📌 Project Overview

This project focuses on analyzing Starbucks beverage data using Python to explore nutritional information, beverage categories, preparation types, and caffeine levels.

The main objective is to clean, process, analyze, and visualize the Starbucks beverage dataset to identify nutritional patterns and gain meaningful insights into the different drinks offered by Starbucks.

## 🎯 Project Objectives

- Clean and preprocess the Starbucks beverage dataset.
- Analyze beverage categories and preparation types.
- Explore calorie, protein, sugar, and fat content.
- Identify beverages with the highest caffeine levels.
- Analyze Vitamin C and other nutritional values.
- Create meaningful visualizations to understand nutritional patterns.

## 🛠️ Technologies & Libraries Used

- **Python** – Programming language
- **Pandas** – Data cleaning and manipulation
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical data visualization
- **Jupyter Notebook** – Development environment

## 📂 Dataset Information

**Dataset:** Starbucks Drink Menu Expanded

The dataset contains beverage information and nutritional attributes, including:

- Beverage
- Beverage Category
- Beverage Preparation
- Calories
- Total Fat (g)
- Trans Fat (g)
- Protein (g)
- Sugars (g)
- Caffeine (mg)
- Iron (% DV)
- Vitamin C (% DV)

## 🧹 Data Cleaning & Preprocessing

The following data cleaning operations were performed:

- Inspected dataset structure and data types.
- Checked missing values and their percentages.
- Converted Total Fat into a numeric format.
- Removed percentage symbols from Iron values and converted them into numerical values.
- Processed caffeine values and handled missing entries.
- Removed unwanted spaces from column names.
- Exported the cleaned dataset into Excel format for further analysis.

## 📊 Exploratory Data Analysis (EDA)

The project includes the following analyses and visualizations:

**1. Category-wise Protein Contribution**
- Explored protein distribution across beverage categories.

**2. Category-wise Calorie Contribution**
- Compared maximum calorie values across beverage categories.

**3. Count of Beverages by Category**
- Identified the distribution of beverages across different categories.

**4. Distribution of Beverage Preparation Types**
- Analyzed the frequency of different beverage preparation methods.

**5. High-Risk Fat Levels**
- Compared maximum trans fat content across beverage categories.

**6. Top 10 Caffeinated Beverages**
- Identified the top 10 beverages with the highest caffeine levels.

**7. Beverage Categories with Highest Sugar Content**
- Compared maximum sugar content across beverage categories.

**8. Vitamin C Contribution in Beverages**
- Identified the top five beverage categories based on maximum Vitamin C content.

## 💡 Key Skills Demonstrated

- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Data Manipulation
- GroupBy Operations
- Missing Value Handling
- Data Type Conversion
- Statistical Analysis
- Data Visualization
- Python Programming

## 📁 Project Structure

```text
Starbucks-Beverage-Nutrition-Analysis/
│
├── starbucks project.ipynb
│
├── starbucks_drinkMenu_expanded.csv
│
├── starbucks_data_cleaned.xlsx
│
└── README.md
```

## 🚀 How to Run This Project

**Step 1:** Clone this repository.

```bash
git clone YOUR_REPOSITORY_LINK
```

**Step 2:** Install the required libraries.

```bash
pip install pandas numpy matplotlib seaborn openpyxl jupyter
```

**Step 3:** Open Jupyter Notebook.

```bash
jupyter notebook
```

**Step 4:** Open `starbucks project.ipynb`.

**Step 5:** Make sure the original CSV dataset is available in the working directory and run the notebook cells sequentially.

## 📌 Project Outcome

Successfully performed data cleaning and exploratory data analysis on the Starbucks beverage dataset.

Created multiple visualizations to understand beverage categories, preparation types, nutritional composition, sugar levels, trans fat content, caffeine levels, and Vitamin C distribution.

This project demonstrates practical Python skills in data preprocessing, analysis, and visualization.

---

## 👨‍💻 Author

**Muhammed Sinan B.I**

**Domain:** Data Science

**Project:** Starbucks Beverage Nutrition Analysis

**Tools:** Python | Pandas | NumPy | Matplotlib | Seaborn
