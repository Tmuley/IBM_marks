# IBM Marks Analysis Project

This project involves analyzing student marks from an Excel file (`IBM-313 Marks.xlsx`) using Python libraries such as `pandas`, `numpy`, and `scipy`. The data includes components like MTE, Mini Projects, ETE, and total scores, and various statistical analyses are performed on the data.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [How to Run](#how-to-run)
- [Statistics and Analysis Performed](#statistics-and-analysis-performed)
- [Visualizations](#visualizations)

## Overview

The dataset provides the marks of 79 students across multiple evaluation categories. The project calculates key statistics, performs data visualization, and derives insights, such as:
- Mean, Median, Mode
- Skewness of data
- Percentile analysis
- Box plot visualization

## Features

- **Data Import and Inspection**: Import Excel data and display an overview of its structure.
- **Statistical Analysis**:
  - Central Tendency (Mean, Median, Mode)
  - Variance, Standard Deviation, and Skewness
  - Quartile and Range calculations
- **Data Visualization**:
  - Boxplot for distribution analysis
  - Line plots with skewness evaluation
- **Python Functions**:
  - Custom functions for calculating min, max, range, and more.

## Technologies Used

- **Programming Language**: Python
- **Libraries**:
  - `pandas` for data handling and manipulation
  - `numpy` for numerical operations
  - `scipy` for statistical analysis
  - `matplotlib` for visualizations

## How to Run

1. Clone this repository:
   ```bash
   git clone <repository_url>
2. Install the required Python packages:
   pip install pandas numpy scipy matplotlib
3.Ensure the Excel file IBM-313 Marks.xlsx is in the project directory
4.Run the script using Python

## Statistics and Analysis Performed

- **Data Overview**:
  - Column summary with data types and non-null counts
  - Example data snippet

- **Central Tendency**:
  - Mean: 46.91
  - Median: 45
  - Mode: 0.0

- **Variance and Standard Deviation**:
  - Variance: 262.78
  - Standard Deviation: 16.21

- **Skewness**:
  - Overall skewness: 0.10 (close to normal distribution)

## Visualizations

### Boxplot
A boxplot is generated to analyze the distribution of total scores across all students.

### Skewness Analysis
Skewness is calculated and demonstrated using line plots for visual interpretation.



