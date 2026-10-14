# YouTube Channel Performance — Exploratory Data Analysis

## Overview

This project explores YouTube channel performance data through Exploratory Data Analysis (EDA). The goal is to understand how video performance metrics relate to each other, identify patterns in audience behavior, and generate hypotheses about what contributes to successful videos.
This is a beginner data science project focused on data exploration, visualization, and interpretation.

## Objectives

- Explore the structure and quality of multiple datasets.
- Analyze distributions, missing values, and potential outliers.
- Investigate relationships between views, watch time, engagement, and revenue.
- Compare average viewing behavior across countries and subscription groups.
- Examine changes in channel metrics over time.
- Generate insights and questions for further analysis.

## Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Analysis

The notebook covers the following topics:

1. **Data inspection and cleaning** — understanding dataset structure and preparing data for analysis.
2. **Univariate analysis** — examining individual variables and their distributions.
3. **Multivariable analysis** — exploring relationships using scatterplots and correlation heatmaps.
4. **Pivot tables** — comparing average viewing metrics across countries and subscription groups.
5. **Time-series analysis** — visualizing how channel metrics change over time.
6. **Exploratory questions** — investigating the relationship between video views, audience retention, and click-through rate, and identifying the most-viewed videos.

## Key Findings

- One video, *How I Would Learn Data Science (If I Had to Start Over)*, substantially outperformed the other top-viewed videos in the dataset.
- Video views did not show an obvious strong relationship with average percentage viewed.
- Click-through rate and average percentage viewed showed a weak positive trend with considerable variation between videos.
- Subscriber and non-subscriber viewing behavior differed in the aggregated data.
- Several engagement and performance metrics were strongly correlated, suggesting that reach and overall video performance are closely related.

These findings are descriptive and apply to the analyzed dataset. Correlation does not establish causation.

## How to Run

1. Clone this repository.
2. Install Python and Jupyter Notebook.
3. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

4. Obtain the source datasets and place them in the locations expected by the notebook.
5. Open `youtube_eda.ipynb` in Jupyter Notebook or VS Code.
6. Run the notebook cells in order.

## Limitations and Future Work

This analysis is exploratory and does not establish the causes of video performance.

Potential extensions include:

- Grouping videos by topic and comparing their performance.
- Analyzing comments to identify recurring audience questions.
- Investigating title and thumbnail characteristics.
- Comparing viral and typical videos.
- Examining the influence of video age on total views.
- Developing a machine learning model to predict video performance.

## Acknowledgments

This project was developed while learning Exploratory Data Analysis, using the [Basic EDA Example](https://www.kaggle.com/code/kenjee/basic-eda-example-section-6) on Kaggle as a learning reference.

The original tutorial and the source datasets should be credited according to their applicable licenses and terms of use.
