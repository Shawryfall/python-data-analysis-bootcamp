# Python Data Analysis Bootcamp

This repository showcases Python data analysis exercises based on a data technician bootcamp.  
It focuses on using **Pandas** and **Matplotlib** to explore, clean, aggregate, and visualise data.

## 📚 Contents

### `notebooks/01_fizzbuzz_basics.ipynb`
Introductory Python exercise implementing the classic FizzBuzz problem:

- Looping from 1 to 100
- Using modulo arithmetic
- Implementing FizzBuzz both as a simple loop and as a reusable function
- Generating a list of FizzBuzz outputs

### `notebooks/02_student_data_analysis.ipynb`
End-to-end analysis of a student performance dataset:

- Loading CSV data with Pandas
- Inspecting structure (`head`, `info`, `describe`)
- Indexing and filtering (selecting columns and rows)
- Creating and transforming columns (`passed`, `score`, `grade`)
- Grouping and aggregation by `class` and `gender`
- Pivot tables to compare average scores
- Sorting by score
- Exporting enriched data to `student_with_grade.csv`
- Visualising score distribution and average score by class

### `notebooks/03_gdp_per_capita_analysis.ipynb`
Exploratory analysis of a GDP per capita dataset:

- Loading and selecting relevant columns
- Handling missing values
- Computing average GDP per capita by **UN region**
- Ranking regions by GDP per capita
- Identifying top and bottom countries by GDP per capita
- Plotting:
  - Bar chart of average GDP per capita by region
  - Bar chart of top 10 countries
  - Histogram of GDP per capita distribution

## 🗂 Data

The datasets used are stored in the `data/` folder:

- `student.csv` — anonymised student performance data
- `gdp_per_capita.csv` — GDP per capita by country/territory and UN region  

## ⚙️ Requirements

To run the notebooks locally, install:

```bash
pip install pandas matplotlib
