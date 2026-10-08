# ⚽ FIFA 19 Data Analysis: Data Cleaning and Visualization

## 📌 Project Overview

**FIFA 19 Data Analysis** is a Python-based data cleaning and visualization project that explores the **FIFA 19 Complete Player Dataset**.

The project focuses on cleaning player data, handling missing values and outliers, and creating meaningful visualizations to identify patterns and relationships between different player attributes.

---

## 🎯 Project Objectives

The main objectives of this project are:

- Clean and prepare the FIFA 19 player dataset.
- Identify and handle missing values.
- Detect and remove duplicate records.
- Check and correct data types and unusual values.
- Detect numerical outliers using the IQR method.
- Analyze important FIFA player attributes.
- Create meaningful visualizations from the cleaned dataset.
- Identify useful patterns and relationships between player attributes.
- Present the analysis in a clear and understandable way.

---

## 📊 Dataset

**Dataset Name:** FIFA 19 Complete Player Dataset

**Source:** Kaggle

The dataset contains detailed information about FIFA 19 players, including:

- Player overall rating
- Potential
- Age
- Nationality
- Position
- Preferred foot
- Value
- Wage
- Height
- Weight
- And other player attributes

The dataset is used to perform data cleaning and exploratory data analysis.

---

## 🧹 Data Cleaning

The data cleaning process was performed using Python and Pandas.

### Steps performed:

- Loaded and explored the FIFA 19 dataset.
- Checked dataset shape and columns.
- Checked data types and summary statistics.
- Identified missing values.
- Handled missing values where required.
- Checked and removed duplicate records.
- Checked unusual or incorrect values.
- Detected numerical outliers using the **IQR method**.
- Capped outliers using the IQR method.
- Created before-and-after box plots for outlier analysis.
- Saved the final cleaned dataset as `FIFA19_cleaned.csv`.

### 📓 Notebook

`01_data_cleaning.ipynb`

---

## 📈 Data Visualizations

After cleaning the dataset, **7 visualizations** were created to explore the FIFA 19 player data.

### Visualizations Included

1. **Graph 01**
2. **Graph 02**
3. **Graph 03**
4. **Graph 04**
5. **Graph 05**
6. **Graph 06**
7. **Graph 07**

The visualizations were created using **Matplotlib** and **Seaborn**.

Each visualization helps in understanding different patterns and relationships present in the FIFA 19 dataset.

### 📓 Visualization Notebook

`02_visualizations.ipynb`

---

## 🔍 Key Analysis Areas

The project focuses on exploring areas such as:

- Player ratings and potential
- Player age distribution
- Player values and wages
- Player positions
- Nationality distribution
- Relationships between numerical player attributes
- Distribution and patterns within FIFA 19 player statistics

---

## 🛠️ Technologies & Libraries

The project was developed using the following tools:

- 🐍 **Python**
- 📊 **Pandas** — Data manipulation and analysis
- 🔢 **NumPy** — Numerical operations
- 📈 **Matplotlib** — Data visualization
- 🎨 **Seaborn** — Statistical visualization
- ☁️ **Google Colab** — Notebook development
- 🐙 **Git** — Version control
- 🐱 **GitHub** — Project hosting and collaboration

---

## 📁 Project Structure

```text
FIFA-19-Data-Analysis/
│
├── README.md
│
├── kl.csv
│
├── FIFA19_cleaned.csv
│
├── 01_data_cleaning.ipynb
│
├── 02_visualizations.ipynb
│
├── 01.png
├── 02.png
├── 03.png
├── 04.png

---

## 👥 Team Members

- **Bhavya Patel (IU2441230594)** — Visualizations
- **Pratham Desai (IU2441230604)** — Data Cleaning


├── 05.png
├── 06.png
└── 07.png
