# Netflix Content Analysis – Dataset Documentation

## Dataset Overview

This project contains an artificially generated Netflix-style dataset consisting of 1,500 records.

The uploaded Excel dataset contains information about content IDs, titles, content types, genres, countries, ratings, dates, release years, durations, directors and descriptions.

The dataset is intended for educational purposes, exploratory data analysis and data visualization practice.

**Disclaimer:** This is a synthetic dataset and is not an official Netflix dataset. Titles, descriptions, directors and statistics are illustrative.

## Dataset Details

| Attribute | Value |
|---|---|
| File Name | Dataset.xlsx |
| File Format | Excel (.xlsx) |
| Sheet Name | Sheet1 |
| Total Records | 1,500 |
| Total Columns | 12 |
| Missing Values | 0 |
| Data Type | Synthetic / Artificially Generated |

## Column Description

| Column | Description |
|---|---|
| Show ID | Unique identifier for each content record |
| Title | Name assigned to the content |
| Type | Content category: Movie or TV Show |
| Genre | Genre classification |
| Country | Country associated with the content |
| Rating | Audience content classification |
| Date Added | Date the content was added in the sample data |
| Year Added | Year of content addition |
| Release Year | Original release year |
| Duration | Movie duration in minutes or TV Show duration in seasons |
| Director | Illustrative director name |
| Description | Short description of the content |

## Dataset Inspection

Initial inspection was performed to understand the dataset structure and quality.

Checks included:

- Total rows and columns.
- Missing value identification.
- Column data types.
- Descriptive statistics.
- Distribution of categorical variables.

The uploaded Excel dataset contains no missing values across its 12 columns.

## Dataset Summary

Based on the uploaded Excel dataset:

### Content Type Distribution

| Type | Count |
|---|---:|
| Movie | 1,026 |
| TV Show | 474 |
| Total | 1,500 |

### Genre Distribution

| Genre | Count |
|---|---:|
| Drama | 337 |
| Comedy | 292 |
| Thriller | 211 |
| Documentary | 206 |
| Other | 190 |
| Action | 160 |
| Romance | 104 |

### Country Distribution

| Country | Count |
|---|---:|
| United States | 475 |
| India | 266 |
| United Kingdom | 190 |
| South Korea | 154 |
| Japan | 104 |
| Canada | 99 |

### Content Ratings

| Rating | Count |
|---|---:|
| TV-MA | 507 |
| TV-14 | 437 |
| TV-PG | 216 |
| R | 157 |
| PG-13 | 122 |
| PG | 35 |
| G | 16 |
| TV-Y7 | 10 |

This generated dataset contains 1,500 records and 9 columns:

1. show_id
2. title
3. type
4. country
5. release_year
6. year_added
7. rating
8. genre
9. duration

It is generated using NumPy with a fixed random seed of 42.

The notebook uses this generated DataFrame for its aggregations and dashboard visualizations.

## Usage

The Excel dataset can be loaded into Python using Pandas:

```python
import pandas as pd

df = pd.read_excel('Dataset.xlsx')

print(df.shape)
print(df.head())
print(df.info())
print(df.isnull().sum())
```

The notebook-generated CSV can be loaded using:

```python
df = pd.read_csv('netflix_sample_data.csv')

print(df.head())
print(df.describe(include='all'))
```

## Potential Analysis Areas

The dataset can be used to explore:

- Movie and TV Show distribution.
- Genre popularity.
- Country-wise content distribution.
- Yearly content additions.
- Audience rating distribution.
- Release year patterns.
- Movie duration analysis.
- TV Show season distribution.
- Director-wise content representation.

## Conclusion

This dataset provides an opportunity to practice data inspection, categorical analysis, grouping, aggregation and visualization using Python.

**Project:** Netflix Content Analysis

**Tools:** Python | Pandas | NumPy | Excel
