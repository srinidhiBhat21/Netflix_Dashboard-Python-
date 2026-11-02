# Netflix Content Analysis 

## Project Overview

This project focuses on analyzing Netflix-style content data using Python and creating a one-page dashboard with Matplotlib.

The objective is to explore content distribution and identify patterns across content types, genres, countries, audience ratings and yearly additions.

The project demonstrates data generation, initial data inspection, data manipulation, aggregation and data visualization using Python.

**Note:** The records used in this portfolio project are artificially generated for educational and analytical purposes. They are not official Netflix data, and the titles and statistics should not be interpreted as actual Netflix catalog information.

## Project Objectives

- Analyze the distribution of Movies and TV Shows.
- Understand content additions across different years.
- Identify the most represented genres.
- Explore country-wise content distribution.
- Examine the distribution of content ratings.
- Present the analysis through a visually structured dashboard.

## Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Data analysis and programming |
| NumPy | Random data generation |
| Pandas | Data manipulation and analysis |
| Matplotlib | Data visualization |
| Jupyter Notebook | Development and execution |
| Excel | Dataset storage and inspection |

## Project Workflow

### 1. Data Generation

Created a reproducible sample dataset containing 1,500 records using NumPy.

The notebook uses a random seed of 42 to ensure reproducibility.

### 2. Data Inspection

Used Pandas to inspect the dataset and understand its structure.

Functions used:
- `df.shape`
- `df.head()`
- `df.isna().sum()`
- `df.describe(include='all')`

### 3. Data Aggregation

Performed grouping and aggregation to prepare the data for visualization.

Functions used:
- `value_counts()`
- `groupby()`
- `size()`
- `reindex()`
- `nunique()`
- `sort_values()`

### 4. Data Visualization

Developed a one-page dashboard using Matplotlib with KPI cards and five visualizations.

## Dashboard Highlights

| Visualization | Analytical Purpose |
|---|---|
| Total Titles | Displays the total number of records |
| Movies | Shows the total movie count |
| TV Shows | Shows the total TV show count |
| Countries | Displays the number of represented countries |
| Titles Added by Year | Identifies yearly content addition patterns |
| Top Genres | Compares the most frequent genres |
| Movies vs TV Shows | Compares content-type distribution |
| Top Countries | Highlights countries with the highest representation |
| Content Ratings | Compares audience rating categories |

## Key Findings

Based on the notebook-generated dataset:

- Total records: 1,500.
- Movies: 1,026 (68.4%).
- TV Shows: 474 (31.6%).
- Countries represented: 10.
- Drama is the most frequent genre.
- The United States has the highest country representation.
- TV-MA is the most frequent content rating.
- Yearly additions are distributed across 2016–2025.

These findings describe the generated sample data only.

## Dataset Information

The repository includes an Excel dataset with 1,500 records and 12 columns.

The notebook also generates a separate CSV dataset with 1,500 records and 9 columns.

**Important:** The uploaded Excel workbook and notebook-generated CSV are different datasets. The dashboard is generated from the notebook's DataFrame, not directly from the uploaded Excel workbook.

Refer to the Dataset README for column descriptions and details.

## Skills Demonstrated

- Python programming
- Data generation using NumPy
- Data inspection using Pandas
- Data aggregation and grouping
- Exploratory Data Analysis
- Matplotlib visualization
- Dashboard design
- Analytical storytelling


*This project is part of my continuous learning journey in Data Analytics, focusing on transforming structured data into meaningful visual insights.*
