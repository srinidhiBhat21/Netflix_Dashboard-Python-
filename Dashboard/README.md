# Netflix Content Analysis – Dashboard

## Overview

This dashboard presents a visual analysis of Netflix-style content using Python's Matplotlib library.

The dashboard is designed as a single-page analytical report with a dark theme, KPI cards and five visualizations.

It provides an overview of content distribution across different categories, helping identify patterns in genres, countries, content types, ratings and yearly additions.

**Important:** This dashboard uses the 1,500-record synthetic DataFrame generated inside `Netflix.ipynb`, rather than directly loading the uploaded Excel dataset.

## Dashboard Components

### 1. KPI Cards

Four KPI cards provide a quick overview of the dataset.

- Total Titles: 1,500
- Movies: 1,026
- TV Shows: 474
- Countries: 10

These indicators summarize the overall content distribution.

### 2. Titles Added by Year

**Chart Type:** Line Chart

Displays the number of titles added each year between 2016 and 2025.

Analytical purpose:
- Understand yearly content addition patterns.
- Identify years with relatively higher additions.
- Observe changes in content additions over time.

### 3. Top Genres

**Chart Type:** Horizontal Bar Chart

Displays the six most frequent genres.

Genres analyzed:
- Drama
- Comedy
- Thriller
- Documentary
- Action
- Romance

Analytical purpose:
- Identify the most represented content categories.
- Compare genre distribution.
- Understand content variety.

### 4. Movies vs TV Shows

**Chart Type:** Donut Chart

Compares the distribution of Movies and TV Shows.

- Movies: 1,026 (68.4%)
- TV Shows: 474 (31.6%)

Analytical purpose:
- Understand the proportion of each content type.
- Identify the dominant content format.

### 5. Top Countries

**Chart Type:** Horizontal Bar Chart

Displays the six countries with the highest content representation.

Countries include:
- United States
- India
- United Kingdom
- South Korea
- Japan
- Canada

Analytical purpose:
- Compare country-wise content representation.
- Identify leading content-producing regions within the sample dataset.

### 6. Content Ratings

**Chart Type:** Bar Chart

Displays the five most frequent audience rating categories.

Categories:
- TV-MA
- TV-14
- TV-PG
- R
- PG-13

Analytical purpose:
- Compare the frequency of different content ratings.
- Understand the audience classification distribution.

## Python Libraries Used

| Library | Application |
|---|---|
| NumPy | Dataset generation |
| Pandas | Grouping and aggregation |
| Matplotlib | Dashboard creation |
| Matplotlib Ticker | Axis formatting utilities |

## Visualization Techniques

- Line plots
- Horizontal bar charts
- Donut charts
- KPI cards
- Custom color palettes
- Chart annotations
- Grid customization
- Figure positioning using `add_axes()`
- Saving dashboard images using `savefig()`

## Design Approach

The dashboard uses a dark background with contrasting red and blue visual elements.

- Dark background for a clean appearance.
- Red for selected highlights and content categories.
- Blue for comparison metrics.
- Light text for readability.
- Minimal chart decorations to maintain focus on the data.

## Conclusion

The dashboard converts the generated dataset into a compact visual report. It demonstrates how Python can be used to summarize data, compare categories and communicate analytical findings through customized visualizations.
